# Đóng góp đầu tiên

<img align="right" width="300" src="assets/fork.png" alt="fork this repository" />  

* Đọc bản hướng dẵn này trong các ngôn ngữ khác:  [Tiếng Anh](README.md), [Tiếng Tây Ban Nha](README.es.md), [Tiếng Hà Lan](README.nl.md), [Tiếng Việt](README.vn.md)*

Nếu bạn không có git trên máy tính của bạn, [ cài đặt nó ]( https://help.github.com/articles/set-up-git/ )

## Fork kho lưu trữ này

Fork kho lưu trữ này bằng cách nhấp vào nút Fork

## Sao chép (clone) kho lưu trữ

<img align="right" width="300" src="assets/clone.png" alt="clone this repository" />  

Bây giờ sao chép kho lưu trữ này vào máy của bạn. Nhấn vào nút clone và sau đó sao chép vào biểu tượng  clipboard

Mở một terminal và chạy lệnh git sau đây:

```
git clone "url bạn vừa sao chép"
```
Trong đó "url bạn vừa sao chép" (không có dấu ngoặc kép) là url dẫn vào kho lưu trữ này. Xem các bước trước đó để có được url.

<img align="right" width="300" src="assets/copy-to-clipboard.png" alt="copy URL to clipboard" />

Ví dụ:
`` `
git clone https://github.com/this-is-you/first-contributions.git
`` `
Trong đó 'this-is-you' là tên người dùng github của bạn. Ở đây bạn đang sao chép nội dung của kho lưu trữ "first-contributions" trong github vào máy tính của bạn

## Tạo một chi nhánh (branch)

Thay đổi thư mục lưu trữ trên máy tính của bạn nếu bạn chưa vào.

```
cd first-contributions
```
Bây giờ tạo ra một chi nhánh sử dụng lệnh `git checkout`
```
git checkout -b <them-ten-ban>
```

Ví dụ:
```
git checkout -b them-Tran-Ly-Vu
```

## Thực hiện những thay đổi cần thiết và chấp nhận những thay đổi này

Bây giờ mở tập tin `Contributors.md` trong một trình soạn thảo văn bản và thêm tên của mình vào nó, sau đó lưu tập tin. Nếu bạn đi đến thư mục dự án và nhập lệnh `git status`, bạn sẽ thấy có những thay đổi. Thêm những thay đổi bằng cách nhập dòng lệnh dưới đây 'git add`.
```
git add Contributors.md
```

Bây giờ chấp nhận những thay đổi bằng cách sử dụng dòng lệnh 'git commit` dưới đây.
```
git commit -m "Them <ten-ban> vào danh sách Cộng tác viên"
```
thay thế `<ten-ban>` với tên của bạn

## Đẩy thay đổi lên github

Đẩy những thay đổi của bạn sử dụng `git push`
```
git push origin <them-ten-ban>
```
Thay thế `<them-ten-ban>` với tên của chi nhánh bạn tạo ra trước đó

## Gửi những thay đổi của bạn để được xem xét

Nếu bạn đi đến kho của bạn trên github, bạn sẽ thấy nút `Compare & pull request`. Nhấp vào nút đó.

<img style="float: right;" src="assets/compare-and-pull.png" alt="create a pull request" />

Bây giờ gửi yêu cầu kéo.

<img style="float: right;" src="assets/submit-pull.png" alt="submit pull request" />

## Giữ fork của bạn được đồng bộ hóa với kho lưu trữ này

Bây giờ tôi sẽ được sáp nhập tất cả các thay đổi của bạn vào chi nhánh chủ của dự án này. Fork của bạn sẽ không có những thay đổi này. Để giữ bản sao của bạn được đồng bộ hóa với kho lưu thữ của tôi, thêm url của kho lưu trữ của tôi như là một `upstream remote url`.
```
git remote add upstream https://github.com/Roshanjossey/first-contributions
```
Đây là một cách để nói git rằng một phiên bản khác của dự án này tồn tại trong url được chỉ định và chúng ta gọi đó là phiên bản chính (master). Một khi các thay đổi được sáp nhập, kéo phiên bản mới của kho lưu trữ của tôi.
```
git fetch upstream
```

Ở đây chúng ta lấy tất cả những thay đổi trong fork của tôi (upstream remote). Bây giờ, bạn cần phải hợp nhất các phiên bản mới của kho của tôi vào chi nhánh chính (master) của bạn.
```
git rebase upstream/master
```
Ở đây bạn đang áp dụng tất cả những thay đổi bạn lấy để đưa vào chi nhánh chính (master). Nếu bạn đẩy chi nhánh chủ bây giờ, bản sao của bạn cũng sẽ có những thay đổi
```
git push origin master
```
Chú ý ở đây bạn đang đẩy lên trên github với chi nhánh tên là origin.

## Tiếp tục tử đây?

Bạn sẽ tìm thấy nhiều vấn đề (issues) dễ cho người bắt đầu tại: [contributor.ninja](https://contributor.ninja).

Dưới đây là một số vấn đề cho người bắt đầu trong các kho lưu trữ phổ biến mà bạn có thể tham gia đóng góp. Nhấn vào những kho lưu trữ này để tìm hiểu thêm

|[![exercism](https://avatars2.githubusercontent.com/u/5624255?v=3&s=100)](https://github.com/exercism/exercism.io/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+first+patch%22)|[![fun-retro](https://avatars3.githubusercontent.com/u/15913975?v=3&s=100)](https://github.com/funretro/distributed/issues?q=is%3Aopen+is%3Aissue+label%3Abeginner-friendly)|[<img width="100" src="https://cdn.worldvectorlogo.com/logos/react.svg">](https://github.com/facebook/react/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+first+bug%22)|[![habitat](https://avatars1.githubusercontent.com/u/18171698?v=3&s=100)](https://github.com/habitat-sh/habitat/issues?q=is%3Aopen+is%3Aissue+label%3AEasy)|[![scikit-learn](https://avatars0.githubusercontent.com/u/365630?v=3&s=100)](https://github.com/scikit-learn/scikit-learn/issues?q=is%3Aopen+is%3Aissue+label%3AEasy)|[<img width="100" src="https://camo.githubusercontent.com/0f302c808c8457f6460913e33aed3478124612c2/687474703a2f2f6c65696e696e67656e2e6f72672f696d672f6c65696e696e67656e2e6a7067">](https://github.com/technomancy/leiningen/issues?q=is%3Aopen+is%3Aissue+label%3ANewbie)|[<img width="100" src="https://images.plot.ly/plotly-documentation/thumbnail/numpy-logo.jpg">](https://github.com/numpy/numpy/issues?q=is%3Aopen+is%3Aissue+label%3A%22Easy+Fix%22)|[![elasticsearch](https://avatars2.githubusercontent.com/u/6764390?v=3&s=100)](https://github.com/elastic/elasticsearch/issues?q=is%3Aopen+is%3Aissue+label%3A%22low+hanging+fruit%22)|
|---|---|---|---|---|---|---|---|
|[exercism](https://github.com/exercism/exercism.io/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+first+patch%22)|[Fun Retros](https://github.com/funretro/distributed/issues?q=is%3Aopen+is%3Aissue+label%3Abeginner-friendly)|[react](https://github.com/facebook/react/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+first+bug%22)|[habitat](https://github.com/habitat-sh/habitat/issues?q=is%3Aopen+is%3Aissue+label%3AEasy)|[scikit-learn](https://github.com/scikit-learn/scikit-learn/issues?q=is%3Aopen+is%3Aissue+label%3AEasy)|[Leiningen](https://github.com/technomancy/leiningen/issues?q=is%3Aopen+is%3Aissue+label%3ANewbie)|[numpy](https://github.com/numpy/numpy/issues?q=is%3Aopen+is%3Aissue+label%3A%22Easy+Fix%22)|[elasticsearch](https://github.com/elastic/elasticsearch/issues?q=is%3Aopen+is%3Aissue+label%3A%22low+hanging+fruit%22)|
|[![homebrew](https://avatars2.githubusercontent.com/u/1503512?v=3&s=100)](https://github.com/Homebrew/brew/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22)|[![rust](https://avatars1.githubusercontent.com/u/5430905?v=3&s=100)](https://github.com/rust-lang/rust/issues?q=is%3Aopen+is%3Aissue+label%3AE-easy)|[![vuejs](https://avatars1.githubusercontent.com/u/6128107?v=3&s=100)](https://github.com/vuejs/vue/issues?q=is%3Aopen+is%3Aissue+label%3A%22contribution+welcome%22)|[![Suave](https://avatars2.githubusercontent.com/u/5822862?v=3&s=100)](https://github.com/SuaveIO/suave/issues?q=is%3Aopen+is%3Aissue+label%3Ahardness-easy)|[![OpenRA](https://avatars3.githubusercontent.com/u/409046?v=3&s=100)](https://github.com/OpenRA/OpenRA/issues?q=is%3Aopen+is%3Aissue+label%3AEasy)|[![PowerShell](https://avatars0.githubusercontent.com/u/11524380?v=3&s=100)](https://github.com/powershell/powershell/issues?q=is%3Aopen+is%3Aissue+label%3AUp-for-Grabs)|[![coala](https://avatars2.githubusercontent.com/u/10620750?v=3&s=100)](https://github.com/coala/coala/issues?q=is%3Aopen+is%3Aissue+label%3Adifficulty%2Flow+label%3Adifficulty%2Fnewcomer)|[![moment](https://avatars2.githubusercontent.com/u/4129662?v=3&s=100)](https://github.com/moment/moment/issues?q=is%3Aopen+is%3Aissue+label%3AUp-For-Grabs)|
|[homebrew](https://github.com/Homebrew/brew/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22)|[Rust](https://github.com/rust-lang/rust/issues?q=is%3Aopen+is%3Aissue+label%3AE-easy)|[vuejs](https://github.com/vuejs/vue/issues?q=is%3Aopen+is%3Aissue+label%3A%22contribution+welcome%22)|[Suave](https://github.com/SuaveIO/suave/issues?q=is%3Aopen+is%3Aissue+label%3Ahardness-easy)|[OpenRA](https://github.com/OpenRA/OpenRA/issues?q=is%3Aopen+is%3Aissue+label%3AEasy)|[PowerShell](https://github.com/powershell/powershell/issues?q=is%3Aopen+is%3Aissue+label%3AUp-for-Grabs)|[coala](https://github.com/coala/coala/issues?q=is%3Aopen+is%3Aissue+label%3Adifficulty%2Flow+label%3Adifficulty%2Fnewcomer)|[moment](https://github.com/moment/moment/issues?q=is%3Aopen+is%3Aissue+label%3AUp-For-Grabs)|
|[![ava](https://avatars0.githubusercontent.com/u/8527916?v=3&s=100)](https://github.com/avajs/ava/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+for+beginner%22)|[![freeCodeCamp](https://avatars0.githubusercontent.com/u/9892522?v=3&s=100)](https://github.com/freeCodeCamp/freeCodeCamp/issues?q=is%3Aopen+is%3Aissue+label%3Afirst-timers-only)|[![webpack](https://avatars3.githubusercontent.com/u/2105791?v=3&s=100)](https://github.com/webpack/webpack/issues?q=is%3Aopen+is%3Aissue+label%3A%22D1%3A+Easy+%28Contrib.+Difficulty%29%22)|[![hoodie](https://avatars1.githubusercontent.com/u/1888826?v=3&s=100)](https://github.com/hoodiehq/hoodie/issues?q=is%3Aopen+is%3Aissue+label%3Afirst-timers-only)|[![pouchdb](https://avatars3.githubusercontent.com/u/3406112?v=3&s=100)](https://github.com/pouchdb/pouchdb/issues?q=is%3Aopen+is%3Aissue+label%3A%22first+timers+only%22)|[![neovim](https://avatars0.githubusercontent.com/u/6471485?v=3&s=100)](https://github.com/neovim/neovim/issues?q=is%3Aopen+is%3Aissue+label%3Aentry-level)|[![babel](https://avatars2.githubusercontent.com/u/9637642?v=3&s=100)](https://github.com/babel/babel/issues?q=is%3Aopen+is%3Aissue+label%3Abeginner-friendly) |[<img width="100" src="https://github.com/adobe/brackets/blob/gh-pages/images/brackets_128.png?raw=true">](https://github.com/adobe/brackets/labels/Starter%20bug)|
|[ava](https://github.com/avajs/ava/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+for+beginner%22)|[freeCodeCamp](https://github.com/freeCodeCamp/freeCodeCamp/issues?q=is%3Aopen+is%3Aissue+label%3Afirst-timers-only)|[webpack](https://github.com/webpack/webpack/issues?q=is%3Aopen+is%3Aissue+label%3A%22D1%3A+Easy+%28Contrib.+Difficulty%29%22)|[hoodie](https://github.com/hoodiehq/hoodie/issues?q=is%3Aopen+is%3Aissue+label%3Afirst-timers-only)|[pouchdb](https://github.com/pouchdb/pouchdb/issues?q=is%3Aopen+is%3Aissue+label%3A%22first+timers+only%22)|[neovim](https://github.com/neovim/neovim/issues?q=is%3Aopen+is%3Aissue+label%3Aentry-level)|[babel](https://github.com/babel/babel/issues?q=is%3Aopen+is%3Aissue+label%3Abeginner-friendly) |[brackets](https://github.com/adobe/brackets/labels/Starter%20bug)|
