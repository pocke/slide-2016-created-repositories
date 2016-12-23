2016年にpockeが作ったものまとめ
=========


---

こんにちは
------


---

だれこれ
-------

---


<img style="width: 30%; border-radius: 50%" alt="ほにゃー" src="pocke.svg">

- Pocke ( Masataka Kuwabara )
- Engineer at Actcat Inc.
- [ハイパーおふとんクリエイター](https://twitter.com/p_ck_/status/809910187708403712)

---

近況
-----


---

GitHub のレポジトリ数が<br>300 超えていました🎉
------

<img src="./300.png" alt="300 repositories">

---

いよいよ今年も終わりですね
-----

---


ということで、今年作ったものをまとめてみました
----

---

プログラマなので…
-----

---


コードを書きました
----

---


条件

- GitHubに今年作ったレポジトリ
- 自分がowner
- public
- forkではない

```ruby
require 'octokit'
repositories = Octokit::Client
  .new(access_token: GITHUB_PERSONAL_ACCESS_TOKEN, auto_paginate: true)
  .repositories(nil, affiliation: 'owner', sort: 'created', visibility: 'public')
  .select{|repo| repo.created_at > Time.new(2016, 1, 1)}
  .reject{|repo| repo.fork}

puts repositories.map(&:to_h).to_json
```


---


けっか
-----


---

[sl-over-http](https://github.com/pocke/sl-over-http) /
[broken-reek-repo](https://github.com/pocke/broken-reek-repo) /
[vueim](https://github.com/pocke/vueim) /
[codecheck-799](https://github.com/pocke/codecheck-799) /
[slide-port-2016-02-06](https://github.com/pocke/slide-port-2016-02-06) /
[vim-textobj-markdown](https://github.com/pocke/vim-textobj-markdown) /
[HelloAgain](https://github.com/pocke/HelloAgain) /
[vim-operator-markdown](https://github.com/pocke/vim-operator-markdown) /
[exec-tcp](https://github.com/pocke/exec-tcp) /
[rspec-l.vim](https://github.com/pocke/rspec-l.vim) /
[vim-operator-trailing-space](https://github.com/pocke/vim-operator-trailing-space) /
[rubocop-rails-order_model_declarative_methods](https://github.com/pocke/rubocop-rails-order_model_declarative_methods) /
[git-back-checkout](https://github.com/pocke/git-back-checkout) /
[vim-operator-ruby-rescue](https://github.com/pocke/vim-operator-ruby-rescue) /
[dotcolon-fonts](https://github.com/pocke/dotcolon-fonts) /
[japan-post-bank-login](https://github.com/pocke/japan-post-bank-login) /
[todofuken](https://github.com/pocke/todofuken) /
[latest-ruby-doc](https://github.com/pocke/latest-ruby-doc) /
[mi](https://github.com/pocke/mi) /
[md-toc](https://github.com/pocke/md-toc) /
[swift-ide-test-comp.vim](https://github.com/pocke/swift-ide-test-comp.vim) /
[rpr](https://github.com/pocke/rpr) /
[pry_testcase](https://github.com/pocke/pry_testcase) /
[about-pocke-slide](https://github.com/pocke/about-pocke-slide) /
[dflint](https://github.com/pocke/dflint) /
[dfast](https://github.com/pocke/dfast) /
[slide-bokuno-kangaeta-saitsuyono-tool](https://github.com/pocke/slide-bokuno-kangaeta-saitsuyono-tool) /
[rails_i18n_lint](https://github.com/pocke/rails_i18n_lint) /
[rails-api-with-cookie-sample](https://github.com/pocke/rails-api-with-cookie-sample) /
[intellij-serverspec-live-templates](https://github.com/pocke/intellij-serverspec-live-templates) /
[serverspec-snippets-generator](https://github.com/pocke/serverspec-snippets-generator) /
[maze](https://github.com/pocke/maze) /
[maze-ui](https://github.com/pocke/maze-ui) /
[rebirth](https://github.com/pocke/rebirth) /
[slide-appraisal](https://github.com/pocke/slide-appraisal) /
[get](https://github.com/pocke/get) /
[slide-template](https://github.com/pocke/slide-template) /
[slide-slack](https://github.com/pocke/slide-slack) /
[stackprof-wrap](https://github.com/pocke/stackprof-wrap) /
[ogp-static](https://github.com/pocke/ogp-static) /
[read-techblog](https://github.com/pocke/read-techblog) /
[cookpad_ec](https://github.com/pocke/cookpad_ec) /
[cookpad-summer-internship-2016-meshitero](https://github.com/pocke/cookpad-summer-internship-2016-meshitero) /
[rrrubocop](https://github.com/pocke/rrrubocop) /
[slide-rrrubocop](https://github.com/pocke/slide-rrrubocop) /
[gulp-stylelint-sourcemap](https://github.com/pocke/gulp-stylelint-sourcemap) /
[git-merge-union-test](https://github.com/pocke/git-merge-union-test) /
[slide-gyakukyujin](https://github.com/pocke/slide-gyakukyujin) /
[reveal-init](https://github.com/pocke/reveal-init) /
[slide-cookpad-dosokai](https://github.com/pocke/slide-cookpad-dosokai) /
[ptmux](https://github.com/pocke/ptmux) /
[sushibar.vim](https://github.com/pocke/sushibar.vim) /
[gry](https://github.com/pocke/gry) /
[rubocop-sniper](https://github.com/pocke/rubocop-sniper)

---

全部で54個ありました!
----

---

上が1月、下が12月です。
----

---

質問タイム！<br>or<br>適当にこの中から語ります！！
----

---

[sl-over-http](https://github.com/pocke/sl-over-http) /
[broken-reek-repo](https://github.com/pocke/broken-reek-repo) /
[vueim](https://github.com/pocke/vueim) /
[codecheck-799](https://github.com/pocke/codecheck-799) /
[slide-port-2016-02-06](https://github.com/pocke/slide-port-2016-02-06) /
[vim-textobj-markdown](https://github.com/pocke/vim-textobj-markdown) /
[HelloAgain](https://github.com/pocke/HelloAgain) /
[vim-operator-markdown](https://github.com/pocke/vim-operator-markdown) /
[exec-tcp](https://github.com/pocke/exec-tcp) /
[rspec-l.vim](https://github.com/pocke/rspec-l.vim) /
[vim-operator-trailing-space](https://github.com/pocke/vim-operator-trailing-space) /
[rubocop-rails-order_model_declarative_methods](https://github.com/pocke/rubocop-rails-order_model_declarative_methods) /
[git-back-checkout](https://github.com/pocke/git-back-checkout) /
[vim-operator-ruby-rescue](https://github.com/pocke/vim-operator-ruby-rescue) /
[dotcolon-fonts](https://github.com/pocke/dotcolon-fonts) /
[japan-post-bank-login](https://github.com/pocke/japan-post-bank-login) /
[todofuken](https://github.com/pocke/todofuken) /
[latest-ruby-doc](https://github.com/pocke/latest-ruby-doc) /
[mi](https://github.com/pocke/mi) /
[md-toc](https://github.com/pocke/md-toc) /
[swift-ide-test-comp.vim](https://github.com/pocke/swift-ide-test-comp.vim) /
[rpr](https://github.com/pocke/rpr) /
[pry_testcase](https://github.com/pocke/pry_testcase) /
[about-pocke-slide](https://github.com/pocke/about-pocke-slide) /
[dflint](https://github.com/pocke/dflint) /
[dfast](https://github.com/pocke/dfast) /
[slide-bokuno-kangaeta-saitsuyono-tool](https://github.com/pocke/slide-bokuno-kangaeta-saitsuyono-tool) /
[rails_i18n_lint](https://github.com/pocke/rails_i18n_lint) /
[rails-api-with-cookie-sample](https://github.com/pocke/rails-api-with-cookie-sample) /
[intellij-serverspec-live-templates](https://github.com/pocke/intellij-serverspec-live-templates) /
[serverspec-snippets-generator](https://github.com/pocke/serverspec-snippets-generator) /
[maze](https://github.com/pocke/maze) /
[maze-ui](https://github.com/pocke/maze-ui) /
[rebirth](https://github.com/pocke/rebirth) /
[slide-appraisal](https://github.com/pocke/slide-appraisal) /
[get](https://github.com/pocke/get) /
[slide-template](https://github.com/pocke/slide-template) /
[slide-slack](https://github.com/pocke/slide-slack) /
[stackprof-wrap](https://github.com/pocke/stackprof-wrap) /
[ogp-static](https://github.com/pocke/ogp-static) /
[read-techblog](https://github.com/pocke/read-techblog) /
[cookpad_ec](https://github.com/pocke/cookpad_ec) /
[cookpad-summer-internship-2016-meshitero](https://github.com/pocke/cookpad-summer-internship-2016-meshitero) /
[rrrubocop](https://github.com/pocke/rrrubocop) /
[slide-rrrubocop](https://github.com/pocke/slide-rrrubocop) /
[gulp-stylelint-sourcemap](https://github.com/pocke/gulp-stylelint-sourcemap) /
[git-merge-union-test](https://github.com/pocke/git-merge-union-test) /
[slide-gyakukyujin](https://github.com/pocke/slide-gyakukyujin) /
[reveal-init](https://github.com/pocke/reveal-init) /
[slide-cookpad-dosokai](https://github.com/pocke/slide-cookpad-dosokai) /
[ptmux](https://github.com/pocke/ptmux) /
[sushibar.vim](https://github.com/pocke/sushibar.vim) /
[gry](https://github.com/pocke/gry) /
[rubocop-sniper](https://github.com/pocke/rubocop-sniper)
