# Ruby_on_Rails_test
Ruby on Rails test
---
## 更新日誌
* 2025/02/06
    * **利用 `rails new new_project (rails new new_project --skip-git)` 建立 new_project (without git) 測試 Ruby on Rials**
    * **在 new_project 利用 `rails server (rails s)` 可執行專案<br> 更換成自己的首頁：<br> 利用 `rails g controller home` 可建立 app/controllers/home_controller.rb 並更新 config/routes.rb 、 app/controllers/home_controller.rb ，新增 app/views/home/index.html.erb 編輯內容為 Hello World!**
    * **利用 `bin/rails generate scaffold User name:string email:string tel:string (rails g scaffold User name email tel)` 、 `rails db:migrate` 實現【使用者功能】：可以新增使用者**
---
## 參考資料
* [ASCII可顯示字元（共95個）](https://zh.wikipedia.org/zh-tw/ASCII#%E5%8F%AF%E6%98%BE%E7%A4%BA%E5%AD%97%E7%AC%A6)
### Git
* [How To Add Line Break To 'git commit -m' From The Command Line?](https://www.geeksforgeeks.org/how-to-add-line-break-to-git-commit-m-from-the-command-line/)
* [Git Commit Message 這樣寫會更好，替專案引入規範與範例](https://ithelp.ithome.com.tw/articles/10228738)
### Ruby
* [Ruby 判断](https://www.runoob.com/ruby/ruby-decision.html)
* [Ruby 运算符](https://www.runoob.com/ruby/ruby-operator.html)
* [Ruby on Rails 30天學習筆記之5－gets、Prompting、Argument](https://ithelp.ithome.com.tw/articles/10156916)
* [Ruby 面向对象](https://www.runoob.com/ruby/ruby-object-oriented.html)
* [二十分鐘 Ruby 體驗](https://www.ruby-lang.org/zh_tw/documentation/quickstart/3/)
* [Ruby 模块（Module）](https://www.runoob.com/ruby/ruby-module.html)
* [Abstract Classes: Ruby on Rails Design Patterns](https://medium.com/nyc-ruby-on-rails/abstract-classes-ruby-on-rails-design-patterns-8eefb58cb087)
* [Abstract methods in ruby?](https://rubytalk.org/t/abstract-methods-in-ruby/39021/7)
* [If Ruby Had Imports…](https://www.fullstackruby.dev/syntax-and-metaprogramming/2020/11/25/if-ruby-had-imports/)
* [Ruby: public, protected 與 private](https://medium.com/@eggyy1224/ruby-public-protected-%E8%88%87-private-bd4a5832a0c8)
* [Private Setter in Ruby](https://kaochenlong.com/2015/03/21/attr_accessor.html)
* [attr_accessor 是幹嘛的？](https://kaochenlong.com/2015/03/21/attr_accessor.html)
* [[Ruby] 物件、類別和模組](https://pjchender.dev/ruby-on-rails/ruby-object/)
### Ruby on Rails
* [快速開發後端程式，為何Ruby on Rails工程師可以常年佔據高收入排行榜前幾名？](https://progressbar.tw/posts/20)
* [[Ruby on Rails] 04. [Windows] 如何在Windows底下安裝Ruby On Rails 開發環境](https://progressbar.tw/posts/122)
* [[Ruby on Rails] 05. [Windows] 安裝程式編輯器與變更網站首頁](https://progressbar.tw/posts/127)
* [rails new silently fails without git #38035](https://github.com/rails/rails/issues/38035)
* [生態圈及簡介](https://railsbook.tw/chapters/01-ecosystem-and-introduction)
* [環境設定](https://railsbook.tw/chapters/02-environment-setup)