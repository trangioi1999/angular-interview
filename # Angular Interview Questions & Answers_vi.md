# Câu hỏi & Trả lời phỏng vấn Angular

> Nhấn :star: nếu bạn thích dự án này và theo dõi [@SudheerJonna](https://twitter.com/SudheerJonna) để cập nhật kỹ thuật mới nhất.

---

<p align="center">
  <a href="https://zerotomastery.io/?utm_source=github&utm_medium=sponsor&utm_campaign=angular-interview-questions">
    <img src="https://process.fs.teachablecdn.com/ADNupMnWyR7kCWRvm76Laz/resize=height:70/https://www.filepicker.io/api/file/AKYtjj5SSGyJuyZrkAB2" alt="ZTM Logo" width="100" height="50">
  </a>
  <p align="center">
    <ol>
    <li>Tham gia <a href="https://links.zerotomastery.io/angular_sudheer">khóa học Angular</a> này để từ người mới bắt đầu trở thành người tự tin xây dựng ứng dụng doanh nghiệp từ đầu</li>
    <li>Tham gia <a href="https://links.zerotomastery.io/mci_sudheer3">bootcamp phỏng vấn lập trình</a> này nếu bạn nghiêm túc muốn được tuyển dụng và không có bằng CNTT</li>
    </ol>
  </p>
</p>

---

### Mục lục

| STT | Câu hỏi |
|---- | ---------
|1 | [Angular Framework là gì?](#angular-framework-la-gi)|
|2 | [Sự khác biệt giữa AngularJS và Angular là gì?](#su-khac-biet-giua-angularjs-va-angular-la-gi)|
|3 | [TypeScript là gì?](#typescript-la-gi)|
|4 | [Vẽ sơ đồ kiến trúc Angular?](#ve-so-do-kien-truc-angular)|
|5 | [Các thành phần chính của Angular là gì?](#cac-thanh-phan-chinh-cua-angular-la-gi)|
|6 | [Directive là gì?](#directive-la-gi)|
|7 | [Component là gì?](#component-la-gi)|
|8 | [Sự khác biệt giữa Component và Directive là gì?](#su-khac-biet-giua-component-va-directive-la-gi)|
|9 | [Template là gì?](#template-la-gi)|
|10| [Module là gì?](#module-la-gi)|
|11| [Có những lifecycle hook nào?](#co-nhung-lifecycle-hook-nao)|
|12| [Data binding là gì?](#data-binding-la-gi)|
|13| [Metadata là gì?](#metadata-la-gi)|
|14| [Angular CLI là gì?](#angular-cli-la-gi)|
|15| [Sự khác biệt giữa constructor và ngOnInit là gì?](#su-khac-biet-giua-constructor-va-ngoninit-la-gi)|
|16| [Service là gì?](#service-la-gi)|
|17| [Dependency injection trong Angular là gì?](#dependency-injection-trong-angular-la-gi)|
|18| [Cách hình thành Dependency Hierarchy?](#cach-hinh-thanh-dependency-hierarchy)|
|19| [Mục đích của async pipe là gì?](#muc-dich-cua-async-pipe-la-gi)|
|20| [Chọn giữa template nội tuyến và file template ngoài như thế nào?](#chon-giua-template-noi-tuyen-va-file-template-ngoai-nhu-the-nao)|
|21| [Mục đích của directive *ngFor là gì?](#muc-dich-cua-directive-ngfor-la-gi)|
|22| [Mục đích của directive ngIf là gì?](#muc-dich-cua-directive-ngif-la-gi)|
|23| [Điều gì xảy ra nếu dùng thẻ script trong template?](#dieu-gi-xay-ra-neu-dung-the-script-trong-template)|
|24| [Interpolation là gì?](#interpolation-la-gi)|
|25| [Template expression là gì?](#template-expression-la-gi)|
|26| [Template statement là gì?](#template-statement-la-gi)|
|27| [Phân loại các kiểu data binding như thế nào?](#phan-loai-cac-kieu-data-binding-nhu-the-nao)|
|28| [Pipe là gì?](#pipe-la-gi)|
|29| [Pipe có tham số là gì?](#pipe-co-tham-so-la-gi)|
|30| [Cách kết hợp nhiều pipe?](#cach-ket-hop-nhieu-pipe)|
|31| [Custom pipe là gì?](#custom-pipe-la-gi)|
|32| [Ví dụ về custom pipe?](#vi-du-ve-custom-pipe)|
|33| [Sự khác biệt giữa pure và impure pipe là gì?](#su-khac-biet-giua-pure-va-impure-pipe-la-gi)|
|34| [Bootstrapping module là gì?](#bootstrapping-module-la-gi)|
|35| [Observable là gì?](#observable-la-gi)|
|36| [HttpClient là gì và lợi ích của nó?](#httpclient-la-gi-va-loi-ich-cua-no)|
|37| [Giải thích cách sử dụng HttpClient với ví dụ?](#giai-thich-cach-su-dung-httpclient-voi-vi-du)|
|38| [Cách đọc toàn bộ response?](#cach-doc-toan-bo-response)|
|39| [Cách xử lý lỗi?](#cach-xu-ly-loi)|
|40| [RxJS là gì?](#rxjs-la-gi)|
|41| [Subscribing là gì?](#subscribing-la-gi)|
|42| [Observable là gì?](#observable-la-gi)|
|43| [Observer là gì?](#observer-la-gi)|
|44| [Sự khác biệt giữa promise và observable là gì?](#su-khac-biet-giua-promise-va-observable-la-gi)|
|45| [Multicasting là gì?](#multicasting-la-gi)|
|46| [Cách xử lý lỗi trong observable?](#cach-xu-ly-loi-trong-observable)|
|47| [Cách viết tắt cho phương thức subscribe?](#cach-viet-tat-cho-phuong-thuc-subscribe)|
|48| [Các hàm tiện ích của RxJS?](#cac-ham-tien-ich-cua-rxjs)|
|49| [Các hàm tạo observable?](#cac-ham-tao-observable)|
|50| [Điều gì xảy ra nếu không cung cấp handler cho observer?](#dieu-gi-xay-ra-neu-khong-cung-cap-handler-cho-observer)|
|51| [Angular elements là gì?](#angular-elements-la-gi)|
|52| [Angular Elements hỗ trợ trình duyệt nào?](#angular-elements-ho-tro-trinh-duyet-nao)|
|53| [Custom elements là gì?](#custom-elements-la-gi)|
|54| [Có cần bootstrap custom elements không?](#co-can-bootstrap-custom-elements-khong)|
|55| [Giải thích cách custom elements hoạt động bên trong?](#giai-thich-cach-custom-elements-hoat-dong-ben-trong)|
|56| [Cách chuyển component thành custom element?](#cach-chuyen-component-thanh-custom-element)|
|57| [Quy tắc ánh xạ giữa Angular component và custom element?](#quy-tac-anh-xa-giua-angular-component-va-custom-element)|
|58| [Cách định nghĩa typings cho custom elements?](#cach-dinh-nghia-typings-cho-custom-elements)|
|59| [Dynamic component là gì?](#dynamic-component-la-gi)|
|60| [Các loại directive khác nhau?](#cac-loai-directive-khac-nhau)|
|61| [Cách tạo directive bằng CLI?](#cach-tao-directive-bang-cli)|
|62| [Ví dụ về attribute directive?](#vi-du-ve-attribute-directive)|
|63| [Angular Router là gì?](#angular-router-la-gi)|
|64| [Mục đích của thẻ base href?](#muc-dich-cua-the-base-href)|
|65| [Các import của router?](#cac-import-cua-router)|
|66| [Router outlet là gì?](#router-outlet-la-gi)|
|67| [Router link là gì?](#router-link-la-gi)|
|68| [Active router link là gì?](#active-router-link-la-gi)|
|69| [Router state là gì?](#router-state-la-gi)|
|70| [Router events là gì?](#router-events-la-gi)|
|71| [Activated route là gì?](#activated-route-la-gi)|
|72| [Cách định nghĩa routes?](#cach-dinh-nghia-routes)|
|73| [Mục đích của Wildcard route?](#muc-dich-cua-wildcard-route)|
|74| [Có luôn cần Routing Module không?](#co-luon-can-routing-module-khong)|
|75| [Angular Universal là gì?](#angular-universal-la-gi)|
|76| [Các loại biên dịch trong Angular?](#cac-loai-bien-dich-trong-angular)|
|77| [JIT là gì?](#jit-la-gi)|
|78| [AOT là gì?](#aot-la-gi)|
|79| [Tại sao cần quá trình biên dịch?](#tai-sao-can-qua-trinh-bien-dich)|
|80| [Ưu điểm của AOT là gì?](#uu-diem-cua-aot-la-gi)|
|81| [Các cách kiểm soát biên dịch AOT?](#cac-cach-kiem-soat-bien-dich-aot)|
|82| [Các giới hạn của metadata?](#cac-gioi-han-cua-metadata)|
|83| [Ba giai đoạn của AOT là gì?](#ba-giai-doan-cua-aot-la-gi)|
|84| [Có thể dùng arrow function trong AOT không?](#co-the-dung-arrow-function-trong-aot-khong)|
|85| [Mục đích của file metadata json là gì?](#muc-dich-cua-file-metadata-json-la-gi)|
|86| [Có thể dùng mọi tính năng javascript cho cú pháp biểu thức trong AOT không?] (#co-the-dung-moi-tinh-nang-javascript-cho-cu-phap-bieu-thuc-trong-aot-khong)|
|87| [Folding là gì?](#folding-la-gi)|
|88| [Macro là gì?](#macro-la-gi)|
|89| [Ví dụ về một số lỗi metadata?](#vi-du-ve-mot-so-loi-metadata)|
|90| [Metadata rewriting là gì?](#metadata-rewriting-la-gi)|
|91| [Cách kế thừa cấu hình?](#cach-ke-thua-cau-hinh)|
|92| [Cách chỉ định tuỳ chọn trình biên dịch template angular?](#cach-chi-dinh-tuy-chon-trinh-bien-dich-template-angular)|
|93| [Cách bật kiểm tra biểu thức binding?](#cach-bat-kiem-tra-bieu-thuc-binding)|
|94| [Mục đích của hàm ép kiểu any là gì?](#muc-dich-cua-ham-ep-kieu-any-la-gi)|
|95| [Toán tử khẳng định không null là gì?](#toan-tu-khang-dinh-khong-null-la-gi)|
|96| [Type narrowing là gì?](#type-narrowing-la-gi)|
|97| [Cách mô tả các dependency trong ứng dụng angular?](#cach-mo-ta-cac-dependency-trong-ung-dung-angular)|
|98| [Zone là gì?](#zone-la-gi)|
|99| [Mục đích của common module là gì?](#muc-dich-cua-common-module-la-gi)|
|100| [Codelyzer là gì?](#codelyzer-la-gi)|
|101| [Angular animation là gì?](#angular-animation-la-gi)|
|102| [Các bước sử dụng animation module?](#cac-buoc-su-dung-animation-module)|
|103| [Hàm State là gì?](#ham-state-la-gi)|
|104| [Hàm Style là gì?](#ham-style-la-gi)|
|105| [Mục đích của hàm animate là gì?](#muc-dich-cua-ham-animate-la-gi)|
|106| [Hàm transition là gì?](#ham-transition-la-gi)|
|107| [Cách inject script động trong angular?](#cach-inject-script-dong-trong-angular)|
|108| [Service worker là gì và vai trò trong Angular?](#service-worker-la-gi-va-vai-tro-trong-angular)|
|109| [Mục tiêu thiết kế của service worker?](#muc-tieu-thiet-ke-cua-service-worker)|
|110| [Sự khác biệt giữa AngularJS và Angular về dependency injection?](#su-khac-biet-giua-angularjs-va-angular-ve-dependency-injection)|
|111| [Angular Ivy là gì?](#angular-ivy-la-gi)|
|112| [Các tính năng có trong ivy preview?](#cac-tinh-nang-co-trong-ivy-preview)|
|113| [Có thể dùng AOT với Ivy không?](#co-the-dung-aot-voi-ivy-khong)|
|114| [Angular Language Service là gì?](#angular-language-service-la-gi)|
|115| [Cách cài đặt angular language service cho dự án?](#cach-cai-dat-angular-language-service-cho-du-an)|
|116| [Có editor nào hỗ trợ Angular Language Service không?](#co-editor-nao-ho-tro-angular-language-service-khong)|
|117| [Giải thích các tính năng của Angular Language Service?](#giai-thich-cac-tinh-nang-cua-angular-language-service)|
|118| [Cách thêm web worker vào ứng dụng?](#cach-them-web-worker-vao-ung-dung)|
|119| [Các giới hạn của web worker?](#cac-gioi-han-cua-web-worker)|
|120| [Angular CLI Builder là gì?](#angular-cli-builder-la-gi)|
|121| [Builder là gì?](#builder-la-gi)|
|122| [Cách gọi builder?](#cach-goi-builder)|
|123| [Cách tạo app shell trong Angular?](#cach-tao-app-shell-trong-angular)|
|124| [Các kiểu case trong Angular?](#cac-kieu-case-trong-angular)|
|125| [Class decorator trong Angular là gì?](#class-decorator-trong-angular-la-gi)|
|126| [Class field decorator là gì?](#class-field-decorator-la-gi)|
|127| [Declarable trong Angular là gì?](#declarable-trong-angular-la-gi)|
|128| [Các giới hạn với declarable class?](#cac-gioi-han-voi-declarable-class)|
|129| [DI token là gì?](#di-token-la-gi)|
|130| [Angular DSL là gì?](#angular-dsl-la-gi)|
|131| [RxJS Subject là gì?](#rxjs-subject-la-gi)|
|132| [Bazel tool là gì?](#bazel-tool-la-gi)|
|133| [Ưu điểm của Bazel tool?](#uu-diem-cua-bazel-tool)|
|134| [Cách dùng Bazel với Angular CLI?](#cach-dung-bazel-voi-angular-cli)|
|135| [Cách chạy Bazel trực tiếp?](#cach-chay-bazel-truc-tiep)|
|136| [Platform trong Angular là gì?](#platform-trong-angular-la-gi)|
|137| [Điều gì xảy ra nếu import cùng một module hai lần?](#dieu-gi-xay-ra-neu-import-cung-mot-module-hai-lan)|
|138| [Cách chọn phần tử trong template component?](#cach-chon-phan-tu-trong-template-component)|
|139| [Cách phát hiện thay đổi route trong Angular?](#cach-phat-hien-thay-doi-route-trong-angular)|
|140| [Cách truyền headers cho HTTP client?](#cach-truyen-headers-cho-http-client)|
|141| [Mục đích của differential loading trong CLI?](#muc-dich-cua-differential-loading-trong-cli)|
|142| [Angular có hỗ trợ dynamic imports không?](#angular-co-ho-tro-dynamic-imports-khong)|
|143| [Lazy loading là gì?](#lazy-loading-la-gi)|
|144| [Workspace API là gì?](#workspace-api-la-gi)|
|145| [Cách nâng cấp phiên bản angular?](#cach-nang-cap-phien-ban-angular)|
|146| [Angular Material là gì?](#angular-material-la-gi)|
|147| [Cách nâng cấp location service của angularjs?](#cach-nang-cap-location-service-cua-angularjs)|
|148| [NgUpgrade là gì?](#ngupgrade-la-gi)|
|149| [Cách test ứng dụng Angular bằng CLI?](#cach-test-ung-dung-angular-bang-cli)|
|150| [Cách dùng polyfills trong ứng dụng Angular?](#cach-dung-polyfills-trong-ung-dung-angular)|
|151| [Các cách kích hoạt change detection trong Angular?](#cac-cach-kich-hoat-change-detection-trong-angular)|
|152| [Sự khác biệt giữa các phiên bản Angular?](#su-khac-biet-giua-cac-phien-ban-angular)|
|153| [Các nguyên tắc bảo mật trong angular?](#cac-nguyen-tac-bao-mat-trong-angular)|
|154| [Lý do loại bỏ Web Tracing Framework?](#ly-do-loai-bo-web-tracing-framework)|
|155| [Lý do loại bỏ các package web worker?](#ly-do-loai-bo-cac-package-web-worker)|
|156| [Cách kiểm tra phiên bản angular CLI?](#cach-kiem-tra-phien-ban-angular-cli)|
|157| [Angular hỗ trợ trình duyệt nào?](#angular-ho-tro-trinh-duyet-nao)|
|158| [Schematic là gì?](#schematic-la-gi)|
|159| [Rule trong Schematics là gì?](#rule-trong-schematics-la-gi)|
|160| [Schematics CLI là gì?](#schematics-cli-la-gi)|
|161| [Các best practice bảo mật trong angular?](#cac-best-practice-bao-mat-trong-angular)|
|162| [Mô hình bảo mật của Angular để ngăn XSS là gì?](#mo-hinh-bao-mat-cua-angular-de-ngan-xss-la-gi)|
|163| [Vai trò của template compiler trong việc ngăn XSS?](#vai-tro-cua-template-compiler-trong-viec-ngan-xss)|
|164| [Các context bảo mật trong Angular?](#cac-context-bao-mat-trong-angular)|
|165| [Sanitization là gì? Angular có hỗ trợ không?](#sanitization-la-gi-angular-co-ho-tro-khong)|
|166| [Mục đích của innerHTML?](#muc-dich-cua-innerhtml)|
|167| [Sự khác biệt giữa nội dung interpolated và innerHTML?](#su-khac-biet-giua-noi-dung-interpolated-va-innerhtml)|
|168| [Cách ngăn tự động sanitization?](#cach-ngan-tu-dong-sanitization)|
|169| [Có an toàn khi dùng trực tiếp API DOM về bảo mật không?](#co-an-toan-khi-dung-truc-tiep-api-dom-ve-bao-mat-khong)|
|170| [DOM sanitizer là gì?](#dom-sanitizer-la-gi)|
|171| [Cách hỗ trợ bảo vệ XSS phía server trong Angular?](#cach-ho-tro-bao-ve-xss-phia-server-trong-angular)|
|172| [Angular có ngăn lỗ hổng HTTP không?](#angular-co-ngan-lo-hong-http-khong)|
|173| [Http Interceptor là gì?](#http-interceptor-la-gi)|
|174| [Ứng dụng của HTTP interceptor?](#ung-dung-cua-http-interceptor)|
|175| [Angular có hỗ trợ nhiều interceptor không?](#angular-co-ho-tro-nhieu-interceptor-khong)|
|176| [Cách dùng interceptor cho toàn bộ ứng dụng?](#cach-dung-interceptor-cho-toan-bo-ung-dung)|
|177| [Angular đơn giản hóa quốc tế hóa (i18n) như thế nào?](#angular-don-gian-hoa-quoc-te-hoa-i18n-nhu-the-nao)|
|178| [Cách đăng ký dữ liệu locale thủ công?](#cach-dang-ky-du-lieu-locale-thu-cong)|
|179| [Bốn giai đoạn dịch template là gì?](#bon-giai-doan-dich-template-la-gi)|
|180| [Mục đích của thuộc tính i18n là gì?](#muc-dich-cua-thuoc-tinh-i18n-la-gi)|
|181| [Mục đích của custom id là gì?](#muc-dich-cua-custom-id-la-gi)|
|182| [Điều gì xảy ra nếu custom id không duy nhất?](#dieu-gi-xay-ra-neu-custom-id-khong-duy-nhat)|
|183| [Có thể dịch văn bản mà không tạo phần tử không?](#co-the-dich-van-ban-ma-khong-tao-phan-tu-khong)|
|184| [Cách dịch thuộc tính?](#cach-dich-thuoc-tinh)|
|185| [Liệt kê các loại số nhiều (pluralization categories)?](#liet-ke-cac-loai-so-nhieu-pluralization-categories)|
|186| [Select ICU expression là gì?](#select-icu-expression-la-gi)|
|187| [Cách báo cáo bản dịch bị thiếu?](#cach-bao-cao-ban-dich-bi-thieu)|
|188| [Cách cấu hình build cho nhiều locale?](#cach-cau-hinh-build-cho-nhieu-locale)|
|189| [Thư viện angular là gì?](#thu-vien-angular-la-gi)|
|190| [AOT compiler là gì?](#aot-compiler-la-gi)|
|191| [Cách chọn phần tử trong template component?](#cach-chon-phan-tu-trong-template-component)|
|192| [TestBed là gì?](#testbed-la-gi)|
|193| [Protractor là gì?](#protractor-la-gi)|
|194| [Collection là gì?](#collection-la-gi)|
|195| [Cách tạo schematics cho thư viện?](#cach-tao-schematics-cho-thu-vien)|
|196| [Cách dùng jquery trong Angular?](#cach-dung-jquery-trong-angular)|
|197| [Nguyên nhân lỗi No provider for HTTP?](#nguyen-nhan-loi-no-provider-for-http)|
|198| [Router state là gì?](#router-state-la-gi)|
|199| [Cách dùng SASS trong dự án angular?](#cach-dung-sass-trong-du-an-angular)|
|200| [Mục đích của thuộc tính hidden?](#muc-dich-cua-thuoc-tinh-hidden)|
|201| [Sự khác biệt giữa ngIf và thuộc tính hidden?](#su-khac-biet-giua-ngif-va-thuoc-tinh-hidden)|
|202| [Slice pipe là gì?](#slice-pipe-la-gi)|
|203| [Thuộc tính index trong directive ngFor là gì?](#thuoc-tinh-index-trong-directive-ngfor-la-gi)|
|204| [Mục đích của ngFor trackBy?](#muc-dich-cua-ngfor-trackby)|
|205| [Mục đích của directive ngSwitch?](#muc-dich-cua-directive-ngswitch)|
|206| [Có thể alias cho inputs và outputs không?](#co-the-alias-cho-inputs-va-outputs-khong)|
|207| [Safe navigation operator là gì?](#safe-navigation-operator-la-gi)|
|208| [Angular9 có cần cấu hình đặc biệt nào không?](#angular9-co-can-cau-hinh-dac-biet-nao-khong)|
|209| [Các thay đổi API TestBed type safe trong Angular9?](#cac-thay-doi-api-testbed-type-safe-trong-angular9)|
|210| [Có bắt buộc truyền static flag cho ViewChild không?](#co-bat-buoc-truyen-static-flag-cho-viewchild-khong)|
|211| [Danh sách các toán tử template expression?](#danh-sach-cac-toan-tu-template-expression)|
|212| [Thứ tự ưu tiên giữa pipe và toán tử ba ngôi?](#thu-tu-uu-tien-giua-pipe-va-toan-tu-ba-ngoi)|
|213| [Entry component là gì?](#entry-component-la-gi)|
|214| [Bootstrapped component là gì?](#bootstrapped-component-la-gi)|
|215| [Cách bootstrap ứng dụng thủ công?](#cach-bootstrap-ung-dung-thu-cong)|
|216| [Bootstrapped component có bắt buộc là entry component không?](#bootstrapped-component-co-bat-buoc-la-entry-component-khong)|
|217| [Routed entry component là gì?](#routed-entry-component-la-gi)|
|218| [Tại sao không cần dùng mảng entryComponents mọi lúc?](#tai-sao-khong-can-dung-mang-entrycomponents-moi-luc)|
|219| [Có cần dùng mảng entryComponents trong Angular9 không?](#co-can-dung-mang-entrycomponents-trong-angular9-khong)|
|220| [Tất cả component đều được sinh ra khi build production?](#tat-ca-component-deu-duoc-sinh-ra-khi-build-production)|
|221| [Angular compiler là gì?](#angular-compiler-la-gi)|
|222| [Vai trò của metadata ngModule trong quá trình biên dịch?](#vai-tro-cua-metadata-ngmodule-trong-qua-trinh-bien-dich)|
|223| [Angular tìm component, directive và pipe như thế nào?](#angular-tim-component-directive-va-pipe-nhu-the-nao)|
|224| [Ví dụ về một số NgModule?](#vi-du-ve-mot-so-ngmodule)|
|225| [Feature module là gì?](#feature-module-la-gi)|
|226| [Các module được import trong feature module do CLI sinh ra?](#cac-module-duoc-import-trong-feature-module-do-cli-sinh-ra)|
|227| [Sự khác biệt giữa ngmodule và javascript module?](#su-khac-biet-giua-ngmodule-va-javascript-module)|
|228| [Các lỗi có thể gặp với declarations?](#cac-loi-co-the-gap-voi-declarations)|
|229| [Các bước sử dụng declaration element?](#cac-buoc-su-dung-declaration-element)|
|230| [Điều gì xảy ra nếu dùng browserModule trong feature module?](#dieu-gi-xay-ra-neu-dung-browsermodule-trong-feature-module)|
|231| [Các loại feature module?](#cac-loai-feature-module)|
|232| [Provider là gì?](#provider-la-gi)|
|233| [Khuyến nghị về phạm vi provider?](#khuyen-nghi-ve-pham-vi-provider)|
|234| [Cách giới hạn phạm vi provider cho một module?](#cach-gioi-han-pham-vi-provider-cho-mot-module)|
|235| [Cách cung cấp service singleton?](#cach-cung-cap-service-singleton)|
|236| [Các cách loại bỏ đăng ký service trùng lặp?](#cac-cach-loai-bo-dang-ky-service-trung-lap)|
|237| [Phương thức forRoot giúp tránh trùng lặp router instance như thế nào?](#phuong-thuc-forroot-giup-tranh-trung-lap-router-instance-nhu-the-nao)|
|238| [Shared module là gì?](#shared-module-la-gi)|
|239| [Có thể chia sẻ service qua module không?](#co-the-chia-se-service-qua-module-khong)|
|240| [Cách lấy hướng hiện tại cho locale?](#cach-lay-huong-hien-tai-cho-locale)|
|241| [Ngcc là gì?](#ngcc-la-gi)|
|242| [Những class nào không nên thêm vào declarations?](#nhung-class-nao-khong-nen-them-vao-declarations)|
|243| [Ngzone là gì?](#ngzone-la-gi)|
|244| [NoopZone là gì?](#noopzone-la-gi)|
|245| [Cách tạo component displayBlock?](#cach-tao-component-displayblock)|
|246| [Các trường hợp thay đổi dữ liệu cho change detection?](#cac-truong-hop-thay-doi-du-lieu-cho-change-detection)|
|247| [Zone context là gì?](#zone-context-la-gi)|
|248| [Các lifecycle hook của zone?](#cac-lifecycle-hook-cua-zone)|
|249| [Các phương thức của NgZone dùng để kiểm soát change detection?](#cac-phuong-thuc-cua-ngzone-dung-de-kiem-soat-change-detection)|
|250| [Cách thay đổi cài đặt zonejs?](#cach-thay-doi-cai-dat-zonejs)|
|251| [Cách kích hoạt animation?](#cach-kich-hoat-animation)|
|252| [Cách cấu hình injector với provider ở các cấp khác nhau?](#cach-cau-hinh-injector-voi-provider-o-cac-cap-khac-nhau)|
|253| [Có bắt buộc dùng injectable cho mọi service class không?](#co-bat-buoc-dung-injectable-cho-moi-service-class-khong)|
|254| [Optional dependency là gì?](#optional-dependency-la-gi)|
|255| [Các loại injector hierarchy?](#cac-loai-injector-hierarchy)|
|256| [Reactive form là gì?](#reactive-form-la-gi)|
|257| [Dynamic form là gì?](#dynamic-form-la-gi)|
|258| [Template driven form là gì?](#template-driven-form-la-gi)|
|259| [Sự khác biệt giữa reactive form và template driven form?](#su-khac-biet-giua-reactive-form-va-template-driven-form)|
|260| [Các cách nhóm form control?](#cac-cach-nhom-form-control)|
|261| [Cách cập nhật thuộc tính cụ thể của form model?](#cach-cap-nhat-thuoc-tinh-cu-the-cua-form-model)|
|262| [Mục đích của FormBuilder?](#muc-dich-cua-formbuilder)|
|263| [Cách kiểm tra thay đổi model trong form?](#cach-kiem-tra-thay-doi-model-trong-form)|
|264| [Các class CSS trạng thái do ngModel cung cấp?](#cac-class-css-trang-thai-do-ngmodel-cung-cap)|
|265| [Cách reset form?](#cach-reset-form)|
|266| [Các loại hàm validator?](#cac-loai-ham-validator)|
|267| [Ví dụ về validator tích hợp sẵn?](#vi-du-ve-validator-tich-hop-san)|
|268| [Cách tối ưu hiệu năng async validator?](#cach-toi-uu-hieu-nang-async-validator)|
|269| [Cách đặt ngFor và ngIf trên cùng một phần tử?](#cach-dat-ngfor-va-ngif-tren-cung-mot-phan-tu)|
|270| [Thuộc tính host trong css là gì?](#thuoc-tinh-host-trong-css-la-gi)|
|271| [Cách lấy route hiện tại?](#cach-lay-route-hien-tai)|
(#what-is-the-benefit-of-automatic-inlining-of-fonts)|
|272| [Component Test Harnesses là gì?](#component-test-harnesses-la-gi)|
|273| [Lợi ích của tự động inline font?](#loi-ich-cua-tu-dong-inline-font)|
|274| [Content projection là gì?](#content-projection-la-gi)|
|275| [Ng-content là gì và mục đích của nó?](#ng-content-la-gi-va-muc-dich-cua-no)|
|276| [Standalone component là gì?](#standalone-component-la-gi)|
|277| [How to create a standalone component uing CLI command?]|
 277 | [Làm cách nào để tạo một component độc lập bằng lệnh CLI?](#lam-cach-nao-de-tao-mot-component-doc-lap-bang-lenh-cli) |
| 278 | [Làm cách nào để tạo một component độc lập một cách thủ công?](#lam-cach-nao-de-tao-mot-component-doc-lap-mot-cach-thu-cong) |
| 279 | [Hydration là gì?](#hydration-la-gi) |
| 280 | [Angular Signals là gì?](#angular-signals-la-gi) |
| 281 | [Giải thích Angular Signals kèm ví dụ](#giai-thich-angular-signals-kem-vi-du) |
| 282 | [Route Parameters là gì? Bạn có thể giải thích từng loại không?](#route-parameters-la-gi-ban-co-the-giai-thich-tung-loai-khong) |
| 283 | [](#) |



1. ### Angular Framework là gì?

   Angular là một **nền tảng front-end mã nguồn mở dựa trên TypeScript** giúp dễ dàng xây dựng các ứng dụng web, di động và máy tính để bàn. Các tính năng chính của framework này bao gồm template khai báo, dependency injection, công cụ end to end giúp việc phát triển ứng dụng dễ dàng hơn.

   **[⬆ Back to Top](#table-of-contents)**

2. ### Sự khác biệt giữa AngularJS và Angular là gì?

   AngularJS (phiên bản 1.x) là một framework JavaScript, trong khi Angular (phiên bản 2+) là một bản viết lại hoàn toàn của AngularJS sử dụng TypeScript, cung cấp hiệu suất tốt hơn, hỗ trợ di động, tính module hóa và kiến trúc hiện đại hơn.

   Dưới đây là một số khác biệt chính được trình bày dưới dạng bảng:-

   | AngularJS                                | Angular                                      |
   | ---------------------------------------- | -------------------------------------------- |
   | Dựa trên kiến trúc MVC                   | Dựa trên Service/Controller                  |
   | Sử dụng JavaScript để xây dựng ứng dụng  | Sử dụng TypeScript để xây dựng ứng dụng      |
   | Dựa trên khái niệm controllers           | Tiếp cận dựa trên component UI               |
   | Không hỗ trợ nền tảng di động            | Hỗ trợ đầy đủ nền tảng di động               |
   | Khó xây dựng ứng dụng thân thiện với SEO | Dễ dàng xây dựng ứng dụng thân thiện với SEO |

   **[⬆ Back to Top](#muc-luc)**

3. ### TypeScript là gì?

   TypeScript là một superset của JavaScript được tạo bởi Microsoft, thêm vào các tính năng tùy chọn như kiểu dữ liệu, lớp, async/await và nhiều tính năng khác, và được biên dịch thành JavaScript thuần túy. Angular được viết hoàn toàn bằng TypeScript như ngôn ngữ chính.
   Bạn có thể cài đặt TypeScript toàn cục bằng cách:

   ```cmd
   npm install -g typescript
   ```

   Hãy xem một ví dụ đơn giản về cách sử dụng TypeScript:-

   ```typescript
   function greeter(person: string) {
     return "Hello, " + person;
   }

   let user = "Sudheer";

   document.body.innerHTML = greeter(user);
   ```

   Phương thức greeter chỉ cho phép đối số kiểu string.

   **[⬆ Back to Top](#muc-luc)**

4. ### Vẽ sơ đồ kiến trúc của Angular?

   Các khối xây dựng chính của một ứng dụng Angular được thể hiện trong sơ đồ dưới đây:-
   ![ScreenShot](images/architecture.png)

   **[⬆ Back to Top](#muc-luc)**

5. ### Các thành phần chính của Angular là gì?

   Angular có các thành phần chính sau:

   1. **Component:** Đây là các khối xây dựng cơ bản của ứng dụng Angular để điều khiển các view HTML.
   2. **Modules:** Một Angular module là một tập hợp các khối xây dựng cơ bản của Angular như components, directives, services v.v. Một ứng dụng được chia thành các phần logic và mỗi phần code được gọi là "module" thực hiện một nhiệm vụ duy nhất.
   3. **Templates:** Đại diện cho các view của ứng dụng Angular.
   4. **Services:** Được sử dụng để tạo các component có thể được chia sẻ trong toàn bộ ứng dụng.
   5. **Metadata:** Có thể được sử dụng để thêm dữ liệu vào một Angular class.

   **[⬆ Back to Top](#muc-luc)**

6. ### Directives là gì?

   Directives thêm hành vi cho một phần tử DOM hiện có hoặc một instance của component hiện có.

   ```typescript
   import { Directive, ElementRef, Input } from "@angular/core";

   @Directive({ selector: "[myHighlight]" })
   export class HighlightDirective {
     constructor(el: ElementRef) {
       el.nativeElement.style.backgroundColor = "yellow";
     }
   }
   ```

   Bây giờ directive này mở rộng hành vi của phần tử HTML với nền màu vàng như dưới đây

   ```html
   <p myHighlight>Highlight me!</p>
   ```

7. ### Components là gì?

   Components là khối xây dựng UI cơ bản nhất của ứng dụng Angular, tạo thành một cây các component Angular. Các component này là một tập con của directives. Không giống như directives, components luôn có một template, và chỉ một component có thể được khởi tạo cho mỗi phần tử trong template.
   Hãy xem một ví dụ đơn giản về Angular component

   ```typescript
   import { Component } from "@angular/core";

   @Component({
     selector: "my-app",
     template: `
       <div>
         <h1>{{ title }}</h1>
         <div>Learn Angular6 with examples</div>
       </div>
     `,
   })
   export class AppComponent {
     title: string = "Welcome to Angular world";
   }
   ```

8. ### Sự khác biệt giữa Component và Directive là gì?

   Tóm tắt ngắn gọn, một component(@component) là một directive-with-a-template.

   Một số khác biệt chính được trình bày dưới dạng bảng

   | Component                                                          | Directive                                                           |
   | ------------------------------------------------------------------ | ------------------------------------------------------------------- |
   | Để đăng ký một component chúng ta sử dụng decorator @Component     | Để đăng ký một directive chúng ta sử dụng decorator @Directive      |
   | Components thường được sử dụng để tạo các widget UI                | Directives được sử dụng để thêm hành vi cho phần tử DOM hiện có     |
   | Component được sử dụng để chia nhỏ ứng dụng thành các phần nhỏ hơn | Directive được sử dụng để thiết kế các component có thể tái sử dụng |
   | Chỉ một component có thể xuất hiện trên mỗi phần tử DOM            | Nhiều directive có thể được sử dụng trên mỗi phần tử DOM            |
   | Bắt buộc phải có decorator @View hoặc templateUrl/template         | Directive không sử dụng View                                        |

9. ### Template là gì?

   Template là một view HTML nơi bạn có thể hiển thị dữ liệu bằng cách binding các điều khiển với các thuộc tính của component Angular. Bạn có thể lưu trữ template của component ở một trong hai vị trí. Bạn có thể định nghĩa nó inline sử dụng thuộc tính template, hoặc bạn có thể định nghĩa template trong một file HTML riêng biệt và liên kết nó trong metadata của component sử dụng thuộc tính templateUrl của decorator @Component.

   **Sử dụng template inline với cú pháp template,**

   ```typescript
   import { Component } from '@angular/core';

   @Component ({
      selector: 'my-app',
      template: '
         <div>
            <h1>{{title}}</h1>
            <div>Learn Angular</div>
         </div>
      '
   })

   export class AppComponent {
      title: string = 'Hello World';
   }
   ```

   **Sử dụng file template riêng biệt như app.component.html**

   ```typescript
   import { Component } from "@angular/core";

   @Component({
     selector: "my-app",
     templateUrl: "app/app.component.html",
   })
   export class AppComponent {
     title: string = "Hello World";
   }
   ```

10. ### Module là gì?

    Module là các ranh giới logic trong ứng dụng của bạn và ứng dụng được chia thành các module riêng biệt để tách biệt chức năng của ứng dụng.
    Hãy xem ví dụ về root module **app.module.ts** được khai báo với decorator **@NgModule** như dưới đây,

    ```typescript
    import { NgModule } from "@angular/core";
    import { BrowserModule } from "@angular/platform-browser";
    import { AppComponent } from "./app.component";

    @NgModule({
      imports: [BrowserModule],
      declarations: [AppComponent],
      bootstrap: [AppComponent],
      providers: [],
    })
    export class AppModule {}
    ```

    NgModule decorator có năm tùy chọn quan trọng (trong tất cả):

    1. Option imports được sử dụng để import các module phụ thuộc khác. BrowserModule được yêu cầu mặc định cho bất kỳ ứng dụng angular web nào.
    2. Option declarations được sử dụng để khai báo các component trong module tương ứng.
    3. Option bootstrap cho Angular biết Component nào cần bootstrap trong ứng dụng.
    4. Option providers được sử dụng để cấu hình tập hợp các đối tượng có thể inject được có sẵn trong injector của module này.
    5. Option entryComponents là tập hợp các component được tải động vào view.

11. ### Các lifecycle hooks có sẵn là gì?

    Ứng dụng Angular trải qua một tập hợp các quy trình hoặc có một vòng đời từ khi khởi tạo đến khi kết thúc ứng dụng.
    Biểu diễn vòng đời dưới dạng hình ảnh như sau,

    ![ScreenShot](images/lifecycle.png)

    Mô tả của từng phương thức lifecycle như dưới đây,

    1. **ngOnChanges:** Khi giá trị của một thuộc tính ràng buộc dữ liệu thay đổi, phương thức này được gọi.
    2. **ngOnInit:** Được gọi khi quá trình khởi tạo của directive/component diễn ra sau khi Angular hiển thị lần đầu tiên các thuộc tính được ràng buộc dữ liệu.
    3. **ngDoCheck:** Dùng để phát hiện và xử lý các thay đổi mà Angular không thể hoặc sẽ không tự phát hiện.
    4. **ngAfterContentInit:** Được gọi sau khi Angular chiếu nội dung bên ngoài vào view của component.
    5. **ngAfterContentChecked:** Được gọi sau khi Angular kiểm tra nội dung được chiếu vào component.
    6. **ngAfterViewInit:** Được gọi sau khi Angular khởi tạo view của component và các view con.
    7. **ngAfterViewChecked:** Được gọi sau khi Angular kiểm tra view của component và các view con.
    8. **ngOnDestroy:** Đây là giai đoạn dọn dẹp ngay trước khi Angular hủy directive/component.

12. ### Data binding là gì?

    Data binding là một khái niệm cốt lõi trong Angular và cho phép định nghĩa giao tiếp giữa component và DOM, giúp dễ dàng định nghĩa các ứng dụng tương tác mà không cần lo lắng về việc đẩy và kéo dữ liệu. Có bốn hình thức data binding (chia làm 3 loại) khác nhau về cách dữ liệu được truyền.

    1. **Từ Component đến DOM:**

       **Interpolation:** {{ value }}: Thêm giá trị của một thuộc tính từ component

       ```html
       <li>Name: {{ user.name }}</li>
       <li>Address: {{ user.address }}</li>
       ```

       **Property binding:** [property]="value": Giá trị được truyền từ component đến thuộc tính được chỉ định hoặc thuộc tính HTML đơn giản

       ```html
       <input type="email" [value]="user.email" />
       ```

    2. **Từ DOM đến Component:**
       **Event binding: (event)="function":** Khi một sự kiện DOM cụ thể xảy ra (ví dụ: click, change, keyup), gọi phương thức được chỉ định trong component
       ```html
       <button (click)="logout()"></button>
       ```
    3. **Binding hai chiều:**
       **Two-way data binding:** [(ngModel)]="value": Binding dữ liệu hai chiều cho phép dữ liệu chảy theo cả hai hướng. Ví dụ, trong đoạn code bên dưới, cả input DOM email và thuộc tính email của component đều đồng bộ với nhau
       ```html
       <input type="email" [(ngModel)]="user.email" />
       ```

13. ### Metadata là gì?

    Metadata được sử dụng để trang trí một class để có thể cấu hình hành vi mong đợi của class đó. Metadata được thể hiện bằng các decorators

    1. **Class decorators**, ví dụ @Component và @NgModule

       ```typescript
       import { NgModule, Component } from "@angular/core";

       @Component({
         selector: "my-component",
         template: "<div>Class decorator</div>",
       })
       export class MyComponent {
         constructor() {
           console.log("Hey I am a component!");
         }
       }

       @NgModule({
         imports: [],
         declarations: [],
       })
       export class MyModule {
         constructor() {
           console.log("Hey I am a module!");
         }
       }
       ```

    2. **Property decorators** Được sử dụng cho các thuộc tính bên trong class, ví dụ @Input và @Output

       ```typescript
       import { Component, Input } from "@angular/core";

       @Component({
         selector: "my-component",
         template: "<div>Property decorator</div>",
       })
       export class MyComponent {
         @Input()
         title: string;
       }
       ```

    3. **Method decorators** Được sử dụng cho các phương thức bên trong class, ví dụ @HostListener

       ```typescript
       import { Component, HostListener } from "@angular/core";

       @Component({
         selector: "my-component",
         template: "<div>Method decorator</div>",
       })
       export class MyComponent {
         @HostListener("click", ["$event"])
         onHostClick(event: Event) {
           // clicked, `event` available
         }
       }
       ```

    4. **Parameter decorators** Được sử dụng cho các tham số bên trong constructor của class, ví dụ @Inject, @Optional

       ```typescript
       import { Component, Inject } from "@angular/core";
       import { MyService } from "./my-service";

       @Component({
         selector: "my-component",
         template: "<div>Parameter decorator</div>",
       })
       export class MyComponent {
         constructor(@Inject(MyService) myService) {
           console.log(myService); // MyService
         }
       }

       // Angular v18 and above

       import { Component, inject } from "@angular/core";
       import { MyService } from "./my-service";

       @Component({
         selector: "my-component",
         template: "<div>Parameter decorator</div>",
       })
       export class MyComponent {
         myService: MyService = inject(MyService);
         constructor() {
           console.log(myService); // MyService
         }
       }
       ```

14. ### Angular CLI là gì?

    Angular CLI(**Command Line Interface**) là một giao diện dòng lệnh để tạo khung và xây dựng các ứng dụng angular sử dụng các module kiểu nodejs (commonJs).
    Bạn cần cài đặt bằng lệnh npm dưới đây,

    ```
    npm install @angular/cli@latest
    ```

    Dưới đây là danh sách một số lệnh hữu ích khi tạo dự án angular

    1. **Tạo dự án mới:** ng new <project-name>

    2. **Tạo Components, Directives & Services:** ng generate/g <feature-name>
       Các loại lệnh khác nhau sẽ là,

       - ng generate class my-new-class: thêm một class vào ứng dụng của bạn
       - ng generate component my-new-component: thêm một component vào ứng dụng của bạn
       - ng generate directive my-new-directive: thêm một directive vào ứng dụng của bạn
       - ng generate enum my-new-enum: thêm một enum vào ứng dụng của bạn
       - ng generate module my-new-module: thêm một module vào ứng dụng của bạn
       - ng generate pipe my-new-pipe: thêm một pipe vào ứng dụng của bạn
       - ng generate service my-new-service: thêm một service vào ứng dụng của bạn

    3. **Chạy dự án:** ng serve

15. ### Sự khác biệt giữa constructor và ngOnInit là gì?

    **Constructor** là phương thức mặc định của class được thực thi khi class được khởi tạo và đảm bảo khởi tạo đúng các trường trong class và các class con của nó. Angular, hay chính xác hơn là Dependency Injector (DI), phân tích các tham số constructor và khi nó tạo một instance mới bằng cách gọi new MyClass() thì cố gắng tìm các providers phù hợp với kiểu của các tham số constructor, giải quyết chúng và truyền vào constructor.  
    **ngOnInit** là một lifecycle hook được gọi bởi Angular để chỉ ra rằng Angular đã hoàn thành việc tạo component.  
    Phần lớn chúng ta sử dụng ngOnInit cho tất cả các khởi tạo/khai báo và tránh thực hiện công việc trong constructor. Constructor chỉ nên được sử dụng để khởi tạo các thành viên của class nhưng không nên thực hiện công việc "thực sự".
    Vì vậy bạn nên sử dụng constructor() để thiết lập Dependency Injection và không nhiều hơn thế. ngOnInit() là nơi tốt hơn để "bắt đầu" - đó là nơi/thời điểm các bindings của components được giải quyết.

    ```typescript
    export class App implements OnInit {
      constructor(private myService: MyService) {
        //được gọi lần đầu tiên trước ngOnInit()
      }

      ngOnInit() {
        //được gọi sau constructor và được gọi sau ngOnChanges() đầu tiên
        //ví dụ: gọi http...
      }
    }
    ```

16. ### Service là gì?

    Service được sử dụng khi một chức năng chung cần được cung cấp cho các module khác nhau. Services cho phép tách biệt các mối quan tâm tốt hơn cho ứng dụng của bạn và tính module hóa tốt hơn bằng cách cho phép bạn tách chức năng chung ra khỏi các components.

    Hãy tạo một repoService có thể được sử dụng trên các components,

    ```typescript
    import { Injectable } from "@angular/core";
    import { Http } from "@angular/http";

    @Injectable({
      // Decorator Injectable là bắt buộc để dependency injection hoạt động
      // Option providedIn đăng ký service với một NgModule cụ thể
      providedIn: "root", // Điều này khai báo service với root app (AppModule)
    })
    export class RepoService {
      constructor(private http: Http) {}

      fetchAll() {
        return this.http.get("https://api.github.com/repositories");
      }
    }
    ```

    Service trên sử dụng Http service như một dependency.

17. ### Dependency injection trong Angular là gì?

    Dependency injection (DI), là một pattern thiết kế ứng dụng quan trọng trong đó một class yêu cầu các dependencies từ nguồn bên ngoài thay vì tự tạo chúng. Angular đi kèm với framework dependency injection riêng của nó để giải quyết các dependencies (services hoặc objects mà một class cần để thực hiện chức năng của nó). Vì vậy, bạn có thể có các services phụ thuộc vào các services khác trong toàn bộ ứng dụng của bạn.

18. ### Dependency Hierarchy được hình thành như thế nào?

    Injectors trong Angular có các quy tắc có thể được tận dụng để đạt được khả năng hiển thị mong muốn của các injectables trong ứng dụng của bạn. Bằng cách hiểu các quy tắc này, bạn có thể xác định nên khai báo provider trong NgModule, Component hoặc Directive nào.

    #### Angular có hai hệ thống injector:

    ![Screenshot](/images/injector%20hierarchies.png)

    #### Module injector

    Khi angular khởi động, nó tạo một root injector nơi các services sẽ được đăng ký, những services này được cung cấp thông qua injectable annotation. Tất cả các services được cung cấp trong thuộc tính `ng-model` được gọi là providers (nếu các module đó không được lazy-loaded).

    Angular đệ quy đi qua tất cả các models đang được sử dụng trong ứng dụng và tạo các instances cho các services được cung cấp trong root injector. Nếu bạn cung cấp một service trong một model được tải eager, service sẽ được thêm vào root injector, điều này làm cho nó có sẵn trong toàn bộ ứng dụng.

    #### Platform Module

    Trong quá trình bootstrapping ứng dụng, angular tạo thêm một vài injectors, phía trên root injector là platform injector, cái này được tạo bởi hàm platform browser dynamic bên trong file `main.ts`, và nó cung cấp một số tính năng đặc thù cho nền tảng như `DomSanitizer`.

    #### NullInjector()

    Ở trên cùng, injector tiếp theo trong hệ thống phân cấp là `NullInjector()`. Trách nhiệm của injector này là ném ra lỗi nếu có thứ gì đó cố gắng tìm dependencies ở đó, trừ khi bạn đã sử dụng `@Optional()` bởi vì cuối cùng, mọi thứ đều kết thúc ở `NullInjector()` và nó trả về lỗi hoặc, trong trường hợp `@Optional()`, trả về `null`.

19. ### Async pipe là gì?

    AsyncPipe đăng ký một observable hoặc promise và trả về giá trị mới nhất mà nó đã phát ra. Khi một giá trị mới được phát ra, pipe đánh dấu component cần được kiểm tra các thay đổi.

    Hãy xem một observable time liên tục cập nhật view mỗi 2 giây với thời gian hiện tại.

    ```typescript
    @Component({
      selector: "async-observable-pipe",
      template: `<div>
        <code>observable|async</code>: Time: {{ time | async }}
      </div>`,
    })
    export class AsyncObservablePipeComponent {
      time: Observable<string>;
      constructor() {
        this.time = new Observable((observer) => {
          setInterval(() => {
            observer.next(new Date().toString());
          }, 2000);
        });
      }
    }
    ```

20. ### Lựa chọn giữa template inline và file template bên ngoài là gì?

    Bạn có thể lưu trữ template của component ở một trong hai vị trí. Bạn có thể định nghĩa nó inline sử dụng thuộc tính **template**, hoặc bạn có thể định nghĩa template trong một file HTML riêng biệt và liên kết nó trong metadata của component sử dụng thuộc tính **templateUrl** của decorator **@Component**.

    Lựa chọn giữa template inline và HTML riêng biệt là vấn đề về sở thích, hoàn cảnh và chính sách tổ chức. Nhưng thông thường chúng ta sử dụng template inline cho phần code nhỏ và file template bên ngoài cho views lớn hơn. Mặc định, Angular CLI tạo components với file template. Nhưng bạn có thể ghi đè điều đó với lệnh bên dưới,

    ```
    ng generate component hero -it
    ```

21. ### Mục đích của directive `*ngFor` là gì?

    Chúng ta sử dụng directive `*ngFor` của Angular trong template để hiển thị từng item trong danh sách. Ví dụ, ở đây chúng ta có thể lặp qua một danh sách users:

    ```html
    <li *ngFor="let user of users">{{ user }}</li>
    ```

    Biến user trong chỉ thị `*ngFor` được đặt trong dấu ngoặc kép là một **biến input template**.

22. ### Mục đích của directive `*ngIf` là gì?

    Đôi khi một ứng dụng cần hiển thị một view hoặc một phần của view chỉ trong những điều kiện cụ thể. Directive `*ngIf` của Angular chèn hoặc xóa một phần tử dựa trên điều kiện đúng/sai. Hãy xem ví dụ hiển thị một thông báo nếu tuổi của user lớn hơn 18:

    ```html
    <p *ngIf="user.age > 18">You are not eligible for student pass!</p>
    ```

    **Lưu ý:** Angular không phải đang hiển thị và ẩn thông báo. Nó đang thêm và xóa phần tử paragraph khỏi DOM. Điều này cải thiện hiệu suất, đặc biệt là trong các dự án lớn với nhiều data bindings.

23. ### Điều gì xảy ra nếu bạn sử dụng thẻ script bên trong template?

    Angular nhận biết giá trị là không an toàn và tự động sanitize nó, loại bỏ thẻ `script` nhưng giữ lại nội dung an toàn như nội dung văn bản của thẻ `script`. Bằng cách này nó loại bỏ nguy cơ tấn công chèn script. Nếu bạn vẫn sử dụng nó thì nó sẽ bị bỏ qua và một cảnh báo xuất hiện trong console của trình duyệt.

    Hãy xem một ví dụ về property binding innerHtml gây ra lỗ hổng XSS,

    ```typescript
    export class InnerHtmlBindingComponent {
      // Ví dụ, một giá trị được kiểm soát bởi user/attacker từ URL.
      htmlSnippet = 'Template <script>alert("0wned")</script> <b>Syntax</b>';
    }
    ```

24. ### Interpolation là gì?

    Interpolation là một cú pháp đặc biệt mà Angular chuyển đổi thành property binding. Đây là một cách thay thế thuận tiện cho property binding. Nó được biểu diễn bằng dấu ngoặc nhọn kép({{}}). Văn bản giữa các dấu ngoặc thường là tên của một thuộc tính component. Angular thay thế tên đó bằng giá trị string của thuộc tính component tương ứng.

    Hãy xem một ví dụ,

    ```html
    <h3>
      {{title}}
      <img src="{{url}}" style="height:30px" />
    </h3>
    ```

    Trong ví dụ trên, Angular đánh giá các thuộc tính title và url và điền vào các chỗ trống, đầu tiên hiển thị tiêu đề ứng dụng in đậm và sau đó là một URL.

25. ### Template expressions là gì?

    Một template expression tạo ra một giá trị tương tự như bất kỳ biểu thức Javascript nào. Angular thực thi biểu thức và gán nó cho một thuộc tính của một đích binding; đích có thể là một phần tử HTML, một component, hoặc một directive. Trong property binding, một template expression xuất hiện trong dấu ngoặc kép ở bên phải của dấu = như trong `[property]="expression"`.
    Trong cú pháp interpolation, template expression được bao quanh bởi dấu ngoặc nhọn kép. Ví dụ, trong interpolation bên dưới, template expression là `{{username}}`,

    ```html
    <h3>{{username}}, welcome to Angular</h3>
    ```

    Các biểu thức javascript sau bị cấm trong template expression

    1. phép gán (=, +=, -=, ...)
    2. new
    3. nối chuỗi biểu thức với ; hoặc ,
    4. toán tử tăng và giảm (++ và --)

26. ### Template statements là gì?

    Một template statement phản hồi một sự kiện được kích hoạt bởi một đích binding như một phần tử, component, hoặc directive. Các template statements xuất hiện trong dấu ngoặc kép ở bên phải của dấu = như `(event)="statement"`.

    Hãy xem một ví dụ về statement của sự kiện click của button

    ```html
    <button (click)="editProfile()">Edit Profile</button>
    ```

    Trong biểu thức trên, editProfile là một template statement. Các biểu thức cú pháp JavaScript sau không được phép.

    1. new
    2. toán tử tăng và giảm, ++ và --
    3. toán tử gán, như += và -=
    4. toán tử bit | và &
    5. các toán tử template expression

27. ### Bạn phân loại các kiểu data binding như thế nào?

    Các kiểu binding có thể được nhóm thành ba loại phân biệt bởi hướng luồng dữ liệu. Chúng được liệt kê như sau,

    1. Từ nguồn-đến-view
    2. Từ view-đến-nguồn
    3. View-đến-nguồn-đến-view

    Cú pháp binding có thể được tổng hợp trong bảng dưới đây,

    | Hướng dữ liệu                      | Cú pháp                                                                | Kiểu                                             |
    | ---------------------------------- | ---------------------------------------------------------------------- | ------------------------------------------------ |
    | Từ nguồn-đến-view(Một chiều)       | 1. {{expression}} 2. [target]="expression" 3. bind-target="expression" | Interpolation, Property, Attribute, Class, Style |
    | Từ view-đến-nguồn(Một chiều)       | 1. (target)="statement" 2. on-target="statement"                       | Event                                            |
    | View-đến-nguồn-đến-view(Hai chiều) | 1. [(target)]="expression" 2. bindon-target="expression"               | Two-way                                          |

28. ### Pipes là gì?

    Pipes là các hàm đơn giản sử dụng [template expressions](#template-expressions-là-gì) để nhận dữ liệu đầu vào và chuyển đổi nó thành đầu ra mong muốn. Ví dụ, hãy xem một pipe để chuyển đổi thuộc tính birthday của component thành một ngày thân thiện với người dùng sử dụng pipe **date**.

    ```typescript
    import { Component } from "@angular/core";

    @Component({
      selector: "app-birthday",
      template: `<p>Birthday is {{ birthday | date }}</p>`,
    })
    export class BirthdayComponent {
      birthday = new Date(1987, 6, 18); // June 18, 1987
    }
    ```

29. ### Pipe có tham số là gì?

    Một pipe có thể chấp nhận bất kỳ số lượng tham số tùy chọn nào để tinh chỉnh đầu ra của nó. Pipe có tham số có thể được tạo bằng cách khai báo tên pipe với dấu hai chấm ( : ) và sau đó là giá trị tham số. Nếu pipe chấp nhận nhiều tham số, phân tách các giá trị bằng dấu hai chấm. Hãy xem ví dụ birthday với một định dạng cụ thể (dd/MM/yyyy):

    ```typescript
    import { Component } from "@angular/core";

    @Component({
      selector: "app-birthday",
      template: `<p>Birthday is {{ birthday | date : "dd/MM/yyyy" }}</p>`, // 18/06/1987
    })
    export class BirthdayComponent {
      birthday = new Date(1987, 6, 18);
    }
    ```

    **Lưu ý:** Giá trị tham số có thể là bất kỳ template expression hợp lệ nào, chẳng hạn như một chuỗi literal hoặc một thuộc tính của component.

30. ### Làm thế nào để bạn nối các pipes?

    Bạn có thể nối các pipes lại với nhau trong các kết hợp có khả năng hữu ích theo nhu cầu. Hãy xem một thuộc tính birthday sử dụng pipe date (cùng với tham số) và pipe uppercase như dưới đây

    ```typescript
    import { Component } from "@angular/core";

    @Component({
      selector: "app-birthday",
      template: `<p>
        Birthday is {{ birthday | date : "fullDate" | uppercase }}
      </p>`, // THURSDAY, JUNE 18, 1987
    })
    export class BirthdayComponent {
      birthday = new Date(1987, 6, 18);
    }
    ```

31. ### Custom pipe là gì?

    Ngoài các pipe có sẵn, bạn có thể viết custom pipe của riêng mình với các đặc điểm chính sau:

    1. Một pipe là một class được trang trí với metadata `@Pipe` decorator, mà bạn import từ thư viện core Angular
       Ví dụ,
       ```typescript
           @Pipe({name: 'myCustomPipe'})
       ```
    2. Class pipe triển khai phương thức transform của interface **PipeTransform** nhận một giá trị đầu vào theo sau là các tham số tùy chọn và trả về giá trị đã được chuyển đổi.
       Cấu trúc của `PipeTransform` sẽ như sau,
       ```typescript
       interface PipeTransform {
         transform(value: any, ...args: any[]): any;
       }
       ```
    3. Decorator `@Pipe` cho phép bạn định nghĩa tên pipe mà bạn sẽ sử dụng trong các template expressions. Nó phải là một định danh JavaScript hợp lệ.
       ```typescript
       template: `{{someInputValue | myCustomPipe: someOtherValue}}`;
       ```

32. ### Cho một ví dụ về custom pipe?

    Bạn có thể tạo các custom pipe có thể tái sử dụng để chuyển đổi giá trị hiện có. Ví dụ, hãy tạo một custom pipe để tìm kích thước file dựa trên một phần mở rộng,

    ```typescript
    import { Pipe, PipeTransform } from "@angular/core";

    @Pipe({ name: "customFileSizePipe" })
    export class FileSizePipe implements PipeTransform {
      transform(size: number, extension: string = "MB"): string {
        return (size / (1024 * 1024)).toFixed(2) + extension;
      }
    }
    ```

    Bây giờ bạn có thể sử dụng pipe trên trong template expression như dưới đây,

    ```typescript
    template: `
          <h2>Find the size of a file</h2>
          <p>Size: {{288966 | customFileSizePipe: 'GB'}}</p>
        `;
    ```

33. ### Sự khác biệt giữa pure và impure pipe là gì?

    Một pure pipe chỉ được gọi khi Angular phát hiện thay đổi trong giá trị hoặc các tham số được truyền vào pipe. Ví dụ, bất kỳ thay đổi nào đối với giá trị đầu vào nguyên thủy (String, Number, Boolean, Symbol) hoặc một tham chiếu đối tượng đã thay đổi (Date, Array, Function, Object). Một impure pipe được gọi cho mỗi chu kỳ phát hiện thay đổi bất kể giá trị hoặc tham số có thay đổi hay không. Nghĩa là, một impure pipe được gọi thường xuyên, thường xuyên như mỗi lần gõ phím hoặc di chuyển chuột.

34. ### Module bootstrapping là gì?

    Mọi ứng dụng có ít nhất một Angular module, module gốc mà bạn bootstrap để khởi chạy ứng dụng được gọi là module bootstrapping. Nó thường được biết đến với tên `AppModule`. Cấu trúc mặc định của `AppModule` được tạo bởi AngularCLI sẽ như sau:

    ```typescript
    import { BrowserModule } from "@angular/platform-browser";
    import { NgModule } from "@angular/core";
    import { FormsModule } from "@angular/forms";
    import { HttpClientModule } from "@angular/common/http";

    import { AppComponent } from "./app.component";

    /* AppModule class với decorator @NgModule */
    @NgModule({
      declarations: [AppComponent],
      imports: [BrowserModule, FormsModule, HttpClientModule],
      providers: [],
      bootstrap: [AppComponent],
    })
    export class AppModule {}
    ```

35. ### Observables là gì?

    Observables là khai báo cung cấp hỗ trợ cho việc truyền thông điệp giữa các publishers và subscribers trong ứng dụng của bạn. Chúng chủ yếu được sử dụng cho việc xử lý sự kiện, lập trình bất đồng bộ, và xử lý nhiều giá trị. Trong trường hợp này, bạn định nghĩa một hàm để phát các giá trị, nhưng nó không được thực thi cho đến khi một consumer đăng ký nó. Consumer đăng ký sau đó nhận được thông báo cho đến khi hàm hoàn thành, hoặc cho đến khi họ hủy đăng ký.

36. ### HttpClient là gì và những lợi ích của nó?

    Hầu hết các ứng dụng Front-end giao tiếp với các dịch vụ backend qua giao thức `HTTP` sử dụng interface `XMLHttpRequest` hoặc API `fetch()`. Angular cung cấp một API HTTP client đơn giản hóa được gọi là `HttpClient` dựa trên interface `XMLHttpRequest`. Client này có sẵn từ package `@angular/common/http`.
    Bạn có thể import nó trong root module của bạn như sau:

    ```typescript
    import { HttpClientModule } from "@angular/common/http";
    ```

    Những lợi ích chính của HttpClient có thể được liệt kê như sau,

    1. Chứa các tính năng có thể test
    2. Cung cấp các đối tượng request và response được định kiểu
    3. Chặn request và response
    4. Hỗ trợ APIs Observable
    5. Hỗ trợ xử lý lỗi hợp lý

37. ### Giải thích cách sử dụng `HttpClient` với một ví dụ?

    Dưới đây là các bước cần thực hiện để sử dụng `HttpClient`.

    1. Import `HttpClient` vào root module:
       ```typescript
       import { HttpClientModule } from '@angular/common/http';
       @NgModule({
         imports: [
           BrowserModule,
           // import HttpClientModule sau BrowserModule.
           HttpClientModule,
         ],
         ......
         })
        export class AppModule {}
       ```
    2. Inject `HttpClient` vào ứng dụng:
       Hãy tạo một userProfileService(`userprofile.service.ts`) làm ví dụ. Nó cũng định nghĩa phương thức get của `HttpClient`:

       ```typescript
       import { Injectable } from "@angular/core";
       import { HttpClient } from "@angular/common/http";

       const userProfileUrl: string = "assets/data/profile.json";

       @Injectable()
       export class UserProfileService {
         constructor(private http: HttpClient) {}

         getUserProfile() {
           return this.http.get(this.userProfileUrl);
         }
       }
       ```

    3. Tạo một component để đăng ký service:
       Hãy tạo một component có tên UserProfileComponent(`userprofile.component.ts`), nó inject `UserProfileService` và gọi phương thức service:
       ```typescript
       fetchUserProfile() {
         this.userProfileService.getUserProfile()
           .subscribe((data: User) => this.user = {
               id: data['userId'],
               name: data['firstName'],
               city: data['city']
           });
       }
       ```
       Vì phương thức service trên trả về một Observable nên cần được đăng ký trong component.

38. ### Làm thế nào bạn có thể đọc response đầy đủ?

    Response body không trả về hoặc có thể không trả về dữ liệu response đầy đủ vì đôi khi servers cũng trả về các headers đặc biệt hoặc status code, điều này rất quan trọng cho workflow của ứng dụng. Để lấy response đầy đủ, bạn nên sử dụng option `observe` từ `HttpClient`:

    ```typescript
    getUserResponse(): Observable<HttpResponse<User>> {
      return this.http.get<User>(
        this.userUrl, { observe: 'response' });
    }
    ```

    Bây giờ phương thức `HttpClient.get()` trả về một Observable của `HttpResponse` đã được định kiểu thay vì chỉ là dữ liệu `JSON`.

39. ### Làm thế nào để thực hiện Error handling?

    Nếu request thất bại trên server hoặc không thể đến được server do vấn đề mạng, thì `HttpClient` sẽ trả về một object error thay vì một response thành công. Trong trường hợp này, bạn cần xử lý trong component bằng cách truyền object `error` như một callback thứ hai cho phương thức `subscribe()`.

    Hãy xem cách nó có thể được xử lý trong component với một ví dụ,

    ```typescript
    fetchUser() {
      this.userService.getProfile()
        .subscribe(
          (data: User) => this.userProfile = { ...data }, // đường dẫn thành công
          error => this.error = error // đường dẫn lỗi
        );
    }
    ```

    Luôn luôn là một ý tưởng tốt để cung cấp cho người dùng một số phản hồi có ý nghĩa thay vì hiển thị đối tượng lỗi thô được trả về từ `HttpClient`.

40. ### RxJS là gì?

    RxJS là một thư viện để soạn thảo code bất đồng bộ và dựa trên callback theo kiểu lập trình hàm, phản ứng sử dụng Observables. Nhiều APIs như HttpClient tạo ra và tiêu thụ RxJS Observables và cũng sử dụng các operators để xử lý observables.

41. ### Subscribe là gì?

    Một instance Observable chỉ bắt đầu phát giá trị khi có ai đó subscribe vào nó. Vì vậy bạn cần subscribe bằng cách gọi phương thức `subscribe()` của instance, truyền vào một đối tượng observer để nhận các thông báo.

    Hãy xem một ví dụ về việc tạo và subscribe vào một observable đơn giản, với một observer ghi log thông điệp nhận được vào console.

    ```typescript
    // Tạo một chuỗi observable gồm 5 số nguyên, bắt đầu từ 1
    const source = range(1, 5);

    // Tạo đối tượng observer
    const myObserver = {
      next: (x) => console.log("Observer nhận được giá trị tiếp theo: " + x),
      error: (err) => console.error("Observer gặp lỗi: " + err),
      complete: () => console.log("Observer nhận được thông báo hoàn thành"),
    };

    // Thực thi với đối tượng observer và In ra từng item
    source.subscribe(myObserver);
    // => Observer nhận được giá trị tiếp theo: 1
    // => Observer nhận được giá trị tiếp theo: 2
    // => Observer nhận được giá trị tiếp theo: 3
    // => Observer nhận được giá trị tiếp theo: 4
    // => Observer nhận được giá trị tiếp theo: 5
    // => Observer nhận được thông báo hoàn thành
    ```

42. ### Observable là gì?

    Observable là một Object độc đáo tương tự như Promise có thể giúp quản lý code bất đồng bộ. Observables không phải là một phần của ngôn ngữ JavaScript nên chúng ta cần dựa vào một thư viện Observable phổ biến gọi là RxJS.
    Các observable được tạo bằng từ khóa new.

    Hãy xem một ví dụ đơn giản về observable,

    ```typescript
    import { Observable } from "rxjs";

    const observable = new Observable((observer) => {
      setTimeout(() => {
        observer.next("Xin chào từ một Observable!");
      }, 2000);
    });
    ```

43. ### Observer là gì?

    Observer là một interface cho một consumer của các thông báo dựa trên push được gửi bởi Observable. Nó có cấu trúc như sau,

    ```typescript
    interface Observer<T> {
      closed?: boolean;
      next: (value: T) => void;
      error: (err: any) => void;
      complete: () => void;
    }
    ```

    Một handler triển khai interface Observer để nhận các thông báo observable sẽ được truyền như một tham số cho observable như sau,

    ```typescript
    myObservable.subscribe(myObserver);
    ```

    **Lưu ý:** Nếu bạn không cung cấp handler cho một loại thông báo, observer sẽ bỏ qua các thông báo của loại đó.

44. ### Sự khác biệt giữa promise và observable là gì?

    Dưới đây là danh sách các khác biệt giữa promise và observable:

    | Observable                                                                                                | Promise                       |
    | --------------------------------------------------------------------------------------------------------- | ----------------------------- |
    | Khai báo: Tính toán không bắt đầu cho đến khi subscribe, nên chúng có thể chạy bất cứ khi nào cần kết quả | Thực thi ngay khi tạo         |
    | Cung cấp nhiều giá trị theo thời gian                                                                     | Chỉ cung cấp một giá trị      |
    | Phương thức subscribe được sử dụng để xử lý lỗi tập trung và dự đoán được                                 | Đẩy lỗi đến các promises con  |
    | Cung cấp chaining và subscription để xử lý các ứng dụng phức tạp                                          | Chỉ sử dụng mệnh đề `.then()` |

45. ### Multicasting là gì?

    Multi-casting là việc phát sóng đến một danh sách nhiều subscribers trong một lần thực thi duy nhất.

    Hãy minh họa tính năng multi-casting:

    ```typescript
    var source = Rx.Observable.from([1, 2, 3]);
    var subject = new Rx.Subject();
    var multicasted = source.multicast(subject);

    // Đây là, bên dưới là, `subject.subscribe({...})`:
    multicasted.subscribe({
      next: (v) => console.log("observerA: " + v),
    });
    multicasted.subscribe({
      next: (v) => console.log("observerB: " + v),
    });
    ```

46. ### Làm thế nào để xử lý lỗi trong observables?

    Bạn có thể xử lý lỗi bằng cách chỉ định một **error callback** trên observer thay vì dựa vào `try`/`catch`, vì chúng không hiệu quả trong môi trường bất đồng bộ.

    Ví dụ, bạn có thể định nghĩa error callback như sau,

    ```typescript
    myObservable.subscribe({
      next(num) {
        console.log("Số tiếp theo: " + num);
      },
      error(err) {
        console.log("Nhận được một lỗi: " + err);
      },
    });
    ```

47. ### Ký hiệu viết tắt cho phương thức subscribe là gì?

    Phương thức `subscribe()` có thể chấp nhận các định nghĩa hàm callback inline, cho các handlers `next`, `error`, và `complete`. Nó được gọi là ký hiệu viết tắt hoặc Phương thức Subscribe với các đối số theo vị trí.

    Ví dụ, bạn có thể định nghĩa phương thức subscribe như sau,

    ```typescript
    myObservable.subscribe(
      (x) => console.log("Observer nhận được giá trị tiếp theo: " + x),
      (err) => console.error("Observer gặp lỗi: " + err),
      () => console.log("Observer nhận được thông báo hoàn thành")
    );
    ```

48. ### Các hàm tiện ích được cung cấp bởi RxJS là gì?

    Thư viện RxJS cũng cung cấp các hàm tiện ích dưới đây để tạo và làm việc với observables.

    1. Chuyển đổi code hiện có cho các hoạt động bất đồng bộ thành observables
    2. Lặp qua các giá trị trong một luồng
    3. Map các giá trị sang các kiểu khác nhau
    4. Lọc các luồng
    5. Kết hợp nhiều luồng

49. ### Các hàm tạo observable là gì?

    RxJS cung cấp các hàm tạo cho quá trình tạo observables từ promises, events, timers và Ajax requests. Hãy giải thích từng cái với một ví dụ:

    1. Tạo một observable từ một promise
       ```typescript
       import { from } from "rxjs"; // hàm from
       const data = from(fetch("/api/endpoint")); //Tạo từ Promise
       data.subscribe({
         next(response) {
           console.log(response);
         },
         error(err) {
           console.error("Lỗi: " + err);
         },
         complete() {
           console.log("Hoàn thành");
         },
       });
       ```
    2. Tạo một observable tạo một request AJAX
       ```typescript
       import { ajax } from "rxjs/ajax"; // hàm ajax
       const apiData = ajax("/api/data"); // Tạo từ AJAX request
       // Subscribe để tạo request
       apiData.subscribe((res) => console.log(res.status, res.response));
       ```
    3. Tạo một observable từ một bộ đếm
       ```typescript
       import { interval } from "rxjs"; // hàm interval
       const secondsCounter = interval(1000); // Tạo từ giá trị Counter
       secondsCounter.subscribe((n) => console.log(`Giá trị Counter: ${n}`));
       ```
    4. Tạo một observable từ một sự kiện
       ```typescript
       import { fromEvent } from "rxjs";
       const el = document.getElementById("custom-element");
       const mouseMoves = fromEvent(el, "mousemove");
       const subscription = mouseMoves.subscribe((e: MouseEvent) => {
         console.log(`Tọa độ của con trỏ chuột: ${e.clientX} * ${e.clientY}`);
       });
       ```

50. ### Điều gì sẽ xảy ra nếu bạn không cung cấp handler cho observer?
    Thông thường, một đối tượng observer có thể định nghĩa bất kỳ kết hợp nào của các handlers loại thông báo `next`, `error`, và `complete`. Nếu bạn không cung cấp handler cho một loại thông báo, observer chỉ đơn giản bỏ qua các thông báo của loại đó.

51. ### Angular elements là gì?

    Angular elements là các Angular components được đóng gói thành **custom elements** (một tiêu chuẩn web để định nghĩa các phần tử HTML mới theo cách độc lập với framework). Angular Elements lưu trữ một Angular component, cung cấp cầu nối giữa dữ liệu và logic được định nghĩa trong component với các API DOM tiêu chuẩn, do đó cung cấp cách để sử dụng các Angular components trong `môi trường không phải Angular`.

52. ### Angular Elements được hỗ trợ trên những trình duyệt nào?

    Vì Angular elements được đóng gói thành custom elements nên sự hỗ trợ của trình duyệt cho angular elements cũng giống như hỗ trợ custom elements.

    Tính năng này hiện đang được hỗ trợ tự nhiên trong một số trình duyệt và đang chờ được hỗ trợ trên các trình duyệt khác.

    | Trình duyệt | Hỗ trợ Angular Element                                                                                                                              |
    | ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
    | Chrome      | Hỗ trợ tự nhiên                                                                                                                                     |
    | Opera       | Hỗ trợ tự nhiên                                                                                                                                     |
    | Safari      | Hỗ trợ tự nhiên                                                                                                                                     |
    | Firefox     | Hỗ trợ tự nhiên từ phiên bản 63 trở lên. Bạn cần bật dom.webcomponents.enabled và dom.webcomponents.customelements.enabled trong các trình duyệt cũ |
    | Edge        | Hiện đang trong quá trình phát triển                                                                                                                |

53. ### Custom elements là gì?

    Custom elements (hay Web Components) là một tính năng của Web Platform cho phép mở rộng HTML bằng cách cho phép bạn định nghĩa một thẻ mà nội dung của nó được tạo và điều khiển bởi mã JavaScript. Trình duyệt duy trì một `CustomElementRegistry` của các custom elements đã được định nghĩa, nó ánh xạ một class JavaScript có thể khởi tạo được với một thẻ HTML. Hiện tại tính năng này được hỗ trợ bởi Chrome, Firefox, Opera và Safari, và có sẵn trong các trình duyệt khác thông qua polyfills.

54. ### Tôi có cần bootstrap custom elements không?

    Không, custom elements tự động bootstrap (hoặc khởi động) khi chúng được thêm vào DOM, và tự động bị hủy khi bị xóa khỏi DOM. Một khi custom element được thêm vào DOM của bất kỳ trang nào, nó trông và hoạt động giống như bất kỳ phần tử HTML nào khác, và không yêu cầu bất kỳ kiến thức đặc biệt nào về Angular.

55. ### Giải thích cách custom elements hoạt động bên trong?

    Dưới đây là các bước theo thứ tự về chức năng của custom elements,

    1. **App đăng ký custom element với trình duyệt:** Sử dụng hàm `createCustomElement()` để chuyển đổi một component thành một class có thể được đăng ký với trình duyệt như một custom element.
    2. **App thêm custom element vào DOM:** Thêm custom element giống như một phần tử HTML có sẵn trực tiếp vào DOM.
    3. **Trình duyệt khởi tạo class dựa trên component:** Trình duyệt tạo một instance của class đã đăng ký và thêm nó vào DOM.
    4. **Instance cung cấp nội dung với data binding và phát hiện thay đổi:** Nội dung trong template được render sử dụng component và dữ liệu DOM.
       Sơ đồ luồng của chức năng custom elements sẽ như sau,

    ![CustomElement](images/customElement.png)

56. ### Làm thế nào để chuyển đổi components thành custom elements?

    Chuyển đổi components thành custom elements bao gồm **hai** bước chính,

    1. **Xây dựng class custom element:** Angular cung cấp hàm `createCustomElement()` để chuyển đổi một Angular component (cùng với các dependencies của nó) thành một custom element. Quá trình chuyển đổi triển khai interface `NgElementConstructor`, và tạo một class constructor được sử dụng để tạo ra một instance tự bootstrap của Angular component.
    2. **Đăng ký class element với trình duyệt:** Nó sử dụng hàm JS `customElements.define()` để đăng ký constructor đã được cấu hình và thẻ custom-element liên quan với `CustomElementRegistry` của trình duyệt. Khi trình duyệt gặp thẻ của element đã đăng ký, nó sử dụng constructor để tạo một instance custom-element.

    Cấu trúc chi tiết sẽ như sau,
    ![CreateElement](images/createElement.png)

57. ### Các quy tắc ánh xạ giữa Angular component và custom element là gì?

    Các thuộc tính và logic của Component được ánh xạ trực tiếp thành các thuộc tính HTML và hệ thống sự kiện của trình duyệt. Hãy mô tả chúng trong hai bước,

    1. API createCustomElement() phân tích các thuộc tính input của component với các thuộc tính tương ứng cho custom element. Ví dụ, component @Input('myInputProp') được chuyển đổi thành thuộc tính custom element `my-input-prop`.
    2. Các outputs của Component được gửi đi như các HTML Custom Events, với tên của custom event khớp với tên output. Ví dụ, component @Output() valueChanged = new EventEmitter() được chuyển đổi thành custom element với sự kiện dispatch là "valueChanged".

58. ### Làm thế nào để định nghĩa typings cho custom elements?

    Bạn có thể sử dụng các types `NgElement` và `WithProperties` được export từ @angular/elements.

    Hãy xem cách nó có thể được áp dụng bằng cách so sánh với Angular component.

    1. Container đơn giản với thuộc tính input sẽ như sau,
       ```typescript
       @Component(...)
       class MyContainer {
         @Input() message: string;
       }
       ```
    2. Sau khi áp dụng types typescript kiểm tra giá trị input và kiểu của chúng,
       ```typescript
       const container = document.createElement("my-container") as NgElement &
         WithProperties<{ message: string }>;
       container.message = "Welcome to Angular elements!";
       container.message = true; // <-- LỖI: TypeScript biết rằng đây phải là một string.
       container.greet = "News"; // <-- LỖI: TypeScript biết rằng không có thuộc tính `greet` trên `container`.
       ```

59. ### Dynamic components là gì?

    Dynamic components là các components mà vị trí của component trong ứng dụng không được định nghĩa tại thời điểm build i.e. chúng không được sử dụng trong bất kỳ template angular nào. Thay vào đó, component được khởi tạo và đặt trong ứng dụng tại thời điểm chạy.

60. ### Các loại directives khác nhau là gì?

    Có chủ yếu ba loại directives:

    1. **Components** — Đây là các directives với một template.
    2. **Structural directives** — Các directives này thay đổi bố cục DOM bằng cách thêm và xóa các phần tử DOM.
    3. **Attribute directives** — Các directives này thay đổi giao diện hoặc hành vi của một phần tử, component, hoặc directive khác.

61. ### Làm thế nào để tạo directives bằng CLI?

    Bạn có thể sử dụng lệnh CLI `ng generate directive` để tạo file class directive. Nó tạo file nguồn(`src/app/components/directivename.directive.ts`), file test tương ứng `.spec.ts` và khai báo file class directive trong root module.

62. ### Cho một ví dụ về attribute directive?

    Hãy lấy hành vi highlighter đơn giản làm ví dụ directive cho phần tử DOM. Bạn có thể tạo và áp dụng attribute directive bằng các bước sau:

    1. Tạo class HighlightDirective với tên file `src/app/highlight.directive.ts`. Trong file này, chúng ta cần import **Directive** từ thư viện core để áp dụng metadata và **ElementRef** trong constructor của directive để inject một tham chiếu đến phần tử DOM host,

       ```typescript
       import { Directive, ElementRef } from "@angular/core";

       @Directive({
         selector: "[appHighlight]",
       })
       export class HighlightDirective {
         constructor(el: ElementRef) {
           el.nativeElement.style.backgroundColor = "red";
         }
       }
       ```

    2. Áp dụng attribute directive như một thuộc tính cho phần tử host(ví dụ, <p>)
       ```html
       <p appHighlight>Highlight me!</p>
       ```
    3. Chạy ứng dụng để xem hành vi highlight trên phần tử paragraph
       ```typescript
       ng serve
       ```

63. ### Angular Router là gì?

    Angular Router là một cơ chế trong đó điều hướng xảy ra từ view này sang view khác khi người dùng thực hiện các tác vụ ứng dụng. Nó mượn các khái niệm hoặc mô hình điều hướng ứng dụng của trình duyệt. Nó cho phép các nhà phát triển xây dựng Ứng dụng Một Trang (Single Page Applications) với nhiều view và cho phép điều hướng giữa các view này.

64. ### Mục đích của thẻ base href là gì?

    Ứng dụng routing cần thêm phần tử <base> vào index.html như phần tử con đầu tiên trong thẻ <head> để chỉ ra cách tạo các URL điều hướng. Nếu thư mục app là thư mục gốc của ứng dụng thì bạn có thể đặt giá trị href như sau

    ```html
    <base href="/" />
    ```

65. ### Các imports của router là gì?

    Angular Router không phải là một phần của Angular Core mà đại diện cho một component view cụ thể cho một URL nhất định. Nó có sẵn trong thư viện có tên `@angular/router` để import các components router cần thiết. Ví dụ, chúng ta import chúng trong app module như sau,

    ```typescript
    import { RouterModule, Routes } from "@angular/router";
    ```

66. ### Router outlet là gì?

    RouterOutlet là một directive từ thư viện router và nó hoạt động như một placeholder đánh dấu vị trí trong template nơi router nên hiển thị các components cho outlet đó. Router outlet được sử dụng như một component,

    ```html
    <router-outlet></router-outlet>
    <!-- Routed components go here -->
    ```

67. ### Router links là gì?

    RouterLink là một directive trên các thẻ anchor cho phép router kiểm soát các phần tử đó. Vì các đường dẫn điều hướng được cố định, bạn có thể gán giá trị string cho directive router-link như dưới đây,

    ```html
    <h1>Angular Router</h1>
    <nav>
      <a routerLink="/todosList">List of todos</a>
      <a routerLink="/completed">Completed todos</a>
    </nav>
    <router-outlet></router-outlet>
    ```

68. ### Active router links là gì?

    RouterLinkActive là một directive toggles các class CSS cho các RouterLink bindings đang hoạt động dựa trên RouterState hiện tại. i.e, Router sẽ thêm các class CSS khi link này đang hoạt động và xóa khi link không hoạt động. Ví dụ, bạn có thể thêm chúng vào RouterLinks như dưới đây.

    ```html
    <h1>Angular Router</h1>
    <nav>
      <a routerLink="/todosList" routerLinkActive="active">List of todos</a>
      <a routerLink="/completed" routerLinkActive="active">Completed todos</a>
    </nav>
    <router-outlet></router-outlet>
    ```

69. ### Router state là gì?

    RouterState là một cây của các routes đã được kích hoạt. Mỗi node trong cây này đều biết về các phân đoạn URL đã được "tiêu thụ", các tham số đã được trích xuất, và dữ liệu đã được giải quyết. Bạn có thể truy cập RouterState hiện tại từ bất kỳ đâu trong ứng dụng bằng cách sử dụng `Router service` và thuộc tính `routerState`.

    ```typescript
    @Component({ templateUrl: "template.html" })
    class MyComponent {
      constructor(router: Router) {
        const state: RouterState = router.routerState;
        const root: ActivatedRoute = state.root;
        const child = root.firstChild;
        const id: Observable<string> = child.params.map((p) => p.id);
        //...
      }
    }
    ```

70. ### Router events là gì?

    Trong mỗi lần điều hướng, Router phát ra các sự kiện điều hướng thông qua thuộc tính Router.events cho phép bạn theo dõi vòng đời của route.

    Chuỗi các sự kiện router như sau,

    1. NavigationStart
    2. RouteConfigLoadStart
    3. RouteConfigLoadEnd
    4. RoutesRecognized
    5. GuardsCheckStart
    6. ChildActivationStart
    7. ActivationStart
    8. GuardsCheckEnd
    9. ResolveStart
    10. ResolveEnd
    11. ActivationEnd
    12. ChildActivationEnd
    13. NavigationEnd
    14. NavigationCancel
    15. NavigationError
    16. Scroll

71. ### Activated route là gì?

    ActivatedRoute chứa thông tin về một route liên kết với một component được tải trong một outlet. Nó cũng có thể được sử dụng để duyệt cây router state. ActivatedRoute sẽ được inject như một service router để truy cập thông tin. Trong ví dụ dưới đây, bạn có thể truy cập đường dẫn route và các tham số,

    ```typescript
    @Component({...})
    class MyComponent {
      constructor(route: ActivatedRoute) {
        const id: Observable<string> = route.params.pipe(map(p => p.id));
        const url: Observable<string> = route.url.pipe(map(segments => segments.join('')));
        // route.data bao gồm cả `data` và `resolve`
        const user = route.data.pipe(map(d => d.user));
      }
    }
    ```

72. ### Làm thế nào để định nghĩa routes?

    Một router phải được cấu hình với một danh sách các route definitions. Bạn cấu hình router với các routes thông qua phương thức `RouterModule.forRoot()`, và thêm kết quả vào mảng `imports` của AppModule.

    ```typescript
     const appRoutes: Routes = [
      { path: 'todo/:id',      component: TodoDetailComponent },
      {
        path: 'todos',
        component: TodosListComponent,
        data: { title: 'Todos List' }
      },
      { path: '',
        redirectTo: '/todos',
        pathMatch: 'full'
      },
      { path: '**', component: PageNotFoundComponent }
    ];

    @NgModule({
      imports: [
        RouterModule.forRoot(
          appRoutes,
          { enableTracing: true } // <-- chỉ dùng cho mục đích debug
        )
        // các imports khác ở đây
      ],
      ...
    })
    export class AppModule { }
    ```

73. ### Mục đích của route Wildcard là gì?

    Nếu URL không khớp với bất kỳ routes được định nghĩa trước nào thì nó sẽ khiến router ném ra lỗi và làm crash ứng dụng. Trong trường hợp này, bạn có thể sử dụng route wildcard. Một route wildcard có path bao gồm hai dấu sao để khớp với mọi URL.

    Ví dụ, bạn có thể định nghĩa PageNotFoundComponent cho route wildcard như sau

    ```typescript
    { path: '**', component: PageNotFoundComponent }
    ```

74. ### Tôi có cần một Routing Module luôn không?

    Không, Routing Module là một lựa chọn thiết kế. Bạn có thể bỏ qua Routing Module (ví dụ, AppRoutingModule) khi cấu hình đơn giản và gộp cấu hình routing trực tiếp vào module đi kèm (ví dụ, AppModule). Nhưng nó được khuyến nghị khi cấu hình phức tạp và bao gồm các service guard và resolver chuyên biệt.

75. ### Angular Universal là gì?

    Angular Universal là một module rendering phía server cho các ứng dụng Angular trong các kịch bản khác nhau. Đây là một dự án do cộng đồng dẫn dắt và có sẵn trong package @angular/platform-server. Gần đây Angular Universal đã được tích hợp với Angular CLI.

76. ### Các loại compilation khác nhau trong Angular là gì?

    Angular cung cấp hai cách để biên dịch ứng dụng của bạn,

    1. Just-in-Time (JIT)
    2. Ahead-of-Time (AOT)

77. ### JIT là gì?

    Just-in-Time (JIT) là một loại biên dịch mà biên dịch ứng dụng của bạn trong trình duyệt tại thời điểm chạy. JIT compilation là mặc định cho đến Angular 8, hiện tại mặc định là AOT. Khi bạn chạy các lệnh CLI ng build (chỉ build) hoặc ng serve (build và chạy local), loại biên dịch (JIT hoặc AOT) phụ thuộc vào giá trị của thuộc tính aot trong cấu hình build được chỉ định trong angular.json. Theo mặc định, aot được đặt là true.

78. ### AOT là gì?

    Ahead-of-Time (AOT) là một loại biên dịch mà biên dịch ứng dụng của bạn tại thời điểm build. Đây là mặc định bắt đầu từ Angular 9. Khi bạn chạy các lệnh CLI ng build (chỉ build) hoặc ng serve (build và chạy local), loại biên dịch (JIT hoặc AOT) phụ thuộc vào giá trị của thuộc tính aot trong cấu hình build được chỉ định trong angular.json. Theo mặc định, aot được đặt là true.

    ```cmd
    ng build
    ng serve
    ```

79. ### Tại sao chúng ta cần quá trình biên dịch?

    Các components và templates của Angular không thể được hiểu trực tiếp bởi trình duyệt. Do đó các ứng dụng Angular yêu cầu một quá trình biên dịch trước khi chúng có thể chạy trong trình duyệt. Ví dụ, trong biên dịch AOT, cả code HTML và TypeScript của Angular được chuyển đổi thành code JavaScript hiệu quả trong giai đoạn build trước khi trình duyệt chạy nó.

80. ### Những lợi ích với AOT là gì?

    Dưới đây là danh sách các lợi ích của AOT,

    1. **Render nhanh hơn:** Trình duyệt tải về một phiên bản đã được biên dịch sẵn của ứng dụng. Vì vậy nó có thể render ứng dụng ngay lập tức mà không cần biên dịch ứng dụng.
    2. **Ít yêu cầu bất đồng bộ hơn:** Nó nhúng các templates HTML và style sheets CSS bên ngoài vào trong javascript của ứng dụng giúp loại bỏ các yêu cầu ajax riêng biệt.
    3. **Kích thước framework Angular tải về nhỏ hơn:** Không yêu cầu tải về Angular compiler. Do đó nó giảm đáng kể kích thước payload của ứng dụng.
    4. **Phát hiện lỗi template sớm hơn:** Phát hiện và báo cáo các lỗi binding template trong bước build
    5. **Bảo mật tốt hơn:** Nó biên dịch các templates HTML và components thành JavaScript. Vì vậy sẽ không có các cuộc tấn công injection.

81. ### Những cách để kiểm soát biên dịch AOT là gì?

    Bạn có thể kiểm soát biên dịch ứng dụng của mình theo hai cách,

    1. Bằng cách cung cấp các tùy chọn template compiler trong file `tsconfig.json`
    2. Bằng cách cấu hình metadata Angular với decorators

82. ### Những hạn chế của metadata là gì?

    Trong Angular, bạn phải viết metadata với các ràng buộc chung sau,

    1. Viết cú pháp biểu thức trong phạm vi các tính năng javascript được hỗ trợ
    2. Compiler chỉ có thể tham chiếu đến các symbols được export
    3. Chỉ gọi các hàm được hỗ trợ bởi compiler
    4. Các thành viên class được trang trí và ràng buộc dữ liệu phải là public.

83. ### Ba giai đoạn của AOT là gì?

    Compiler AOT hoạt động trong ba giai đoạn,

    1. **Phân tích Code:** Compiler ghi lại một biểu diễn của source
    2. **Code generation:** Nó xử lý việc giải thích cũng như đặt các hạn chế trên những gì nó giải thích.
    3. **Validation:** Trong giai đoạn này, Angular template compiler sử dụng TypeScript compiler để xác thực các biểu thức binding trong templates.

84. ### Tôi có thể sử dụng arrow functions trong AOT không?

    Không, Arrow functions hoặc lambda functions không thể được sử dụng để gán giá trị cho các thuộc tính decorator. Ví dụ, đoạn code sau không hợp lệ:

    ```typescript
    @Component({
      providers: [{
        provide: MyService, useFactory: () => getService()
      }]
    })
    ```

    Để sửa điều này, nó phải được thay đổi thành hàm được export như sau:

    ```typescript
    function getService(){
      return new MyService();
    }

    @Component({
      providers: [{
        provide: MyService, useFactory: getService
      }]
    })
    ```

    Nếu bạn vẫn sử dụng arrow function, nó sẽ tạo ra một node lỗi tại vị trí của hàm. Khi compiler sau đó giải thích node này, nó báo cáo một lỗi để chuyển arrow function thành một hàm được export.
    **Lưu ý:** Từ Angular5 trở đi, compiler tự động thực hiện việc viết lại này trong khi phát file .js.

85. ### Mục đích của các file metadata json là gì?

    File metadata.json có thể được coi như một sơ đồ của cấu trúc tổng thể của metadata của một decorator, được biểu diễn dưới dạng cây cú pháp trừu tượng(AST). Trong giai đoạn phân tích, collector AOT quét metadata được ghi lại trong các decorators Angular và xuất thông tin metadata trong các file .metadata.json, một file cho mỗi file .d.ts.

86. ### Tôi có thể sử dụng bất kỳ tính năng javascript nào cho cú pháp biểu thức trong AOT không?

    Không, collector AOT hiểu một tập con (hoặc giới hạn) của các tính năng JavaScript. Nếu một biểu thức sử dụng cú pháp không được hỗ trợ, collector sẽ ghi một node lỗi vào file .metadata.json. Về sau, compiler sẽ báo cáo lỗi nếu nó cần phần metadata đó để tạo mã ứng dụng.

87. ### Folding là gì?

    Compiler chỉ có thể giải quyết các tham chiếu đến các symbols được export trong metadata. Trong khi đó một số thành viên không được export được folded trong khi tạo mã. i.e Folding là một quá trình trong đó collector đánh giá một biểu thức trong quá trình thu thập và ghi kết quả vào .metadata.json thay vì biểu thức gốc.
    Ví dụ, compiler không thể tham chiếu đến selector vì nó không được export

    ```typescript
    let selector = 'app-root';
    @Component({
      selector: selector
    })
    ```

    Sẽ được folded thành selector inline

    ```typescript
    @Component({
          selector: 'app-root'
        })
    ```

    Nhớ rằng compiler không thể fold mọi thứ. Ví dụ, toán tử spread trên mảng, đối tượng được tạo bằng từ khóa new và lời gọi hàm.

88. ### Macros là gì?

    AOT compiler hỗ trợ macros dưới dạng các hàm hoặc phương thức static trả về một biểu thức trong `một biểu thức return đơn`.
    Ví dụ, hãy xem một hàm macro dưới đây,

    ```typescript
    export function wrapInArray<T>(value: T): T[] {
      return [value];
    }
    ```

    Bạn có thể sử dụng nó bên trong metadata như một biểu thức,

    ```typescript
    @NgModule({
      declarations: wrapInArray(TypicalComponent),
    })
    export class TypicalModule {}
    ```

    Compiler xử lý biểu thức macro như nó được viết trực tiếp

    ```typescript
    @NgModule({
      declarations: [TypicalComponent],
    })
    export class TypicalModule {}
    ```

89. ### Cho một ví dụ về một số lỗi metadata?

    Dưới đây là một số lỗi gặp phải trong metadata,

    1. **Expression form not supported:** Một số tính năng ngôn ngữ nằm ngoài cú pháp biểu thức bị giới hạn của compiler được sử dụng trong angular metadata có thể tạo ra lỗi này.
       Hãy xem một số ví dụ này,
       ```typescript
       1. export class User { ... }
          const prop = typeof User; // typeof không hợp lệ trong metadata
       2. { provide: 'token', useValue: { [prop]: 'value' } }; // ký hiệu ngoặc vuông không hợp lệ trong metadata
       ```
    2. **Reference to a local (non-exported) symbol:** Compiler gặp một tham chiếu đến một symbol được định nghĩa cục bộ mà không được export hoặc không được khởi tạo.
       Hãy xem ví dụ về lỗi này,

       ```typescript
       // LỖI
       let username: string; // không được export cũng không được khởi tạo

       @Component({
         selector: 'my-component',
         template: ... ,
         providers: [
           { provide: User, useValue: username }
         ]
       })
       export class MyComponent {}
       ```

       Bạn có thể sửa điều này bằng cách export hoặc khởi tạo giá trị,

       ```typescript
       export let username: string; // đã export
       hoặc;
       let username = "John"; // đã khởi tạo
       ```

    3. **Function calls are not supported:** Compiler hiện không hỗ trợ các biểu thức hàm hoặc hàm lambda. Ví dụ, bạn không thể đặt useFactory của provider thành một hàm ẩn danh hoặc arrow function như dưới đây.
       ```typescript
        providers: [
           { provide: MyStrategy, useFactory: function() { ... } },
           { provide: OtherStrategy, useFactory: () => { ... } }
         ]
       ```
       Bạn có thể sửa điều này với hàm được export
       ```typescript
       export function myStrategy() { ... }
       export function otherStrategy() { ... }
       ... // metadata
       providers: [
           { provide: MyStrategy, useFactory: myStrategy },
           { provide: OtherStrategy, useFactory: otherStrategy },
       ```
    4. **Destructured variable or constant not supported:** Compiler không hỗ trợ các tham chiếu đến các biến được gán bởi destructuring.
       Ví dụ, bạn không thể viết như thế này:

       ```typescript
       import { user } from './user';

       // gán destructuring cho name và age
       const {name, age} = user;
       ... //metadata
       providers: [
           {provide: Name, useValue: name},
           {provide: Age, useValue: age},
         ]
       ```

       Bạn có thể sửa điều này bằng các giá trị không destructured

       ```typescript
       import { user } from './user';
       ... //metadata
       providers: [
           {provide: Name, useValue: user.name},
           {provide: Age, useValue: user.age},
         ]
       ```

90. ### Metadata rewriting là gì?

    Metadata rewriting là quá trình trong đó compiler chuyển đổi biểu thức khởi tạo các trường như useClass, useValue, useFactory và data thành một biến được export, thay thế biểu thức. Nhớ rằng compiler thực hiện việc viết lại này trong quá trình phát file .js nhưng không trong các file định nghĩa (.d.ts file).

91. ### Làm thế nào để cung cấp inheritance cấu hình?

    Angular Compiler hỗ trợ inheritance cấu hình thông qua extends trong tsconfig.json trên angularCompilerOptions. i.e, Cấu hình từ file cơ sở (ví dụ, tsconfig.base.json) được tải trước, sau đó bị ghi đè bởi cấu hình trong file kế thừa.

    ```typescript
    {
      "extends": "../tsconfig.base.json",
      "compilerOptions": {
        "experimentalDecorators": true,
        ...
      },
      "angularCompilerOptions": {
        "fullTemplateTypeCheck": true,
        "preserveWhitespaces": true,
        ...
      }
    }
    ```

92. ### Làm thế nào để chỉ định các tùy chọn angular template compiler?

    Các tùy chọn angular template compiler được chỉ định như các thành viên của đối tượng **angularCompilerOptions** trong file tsconfig.json. Các tùy chọn này sẽ được chỉ định bên cạnh các tùy chọn typescript compiler.

    ```typescript
    {
      "compilerOptions": {
        "experimentalDecorators": true,
                  ...
      },
      "angularCompilerOptions": {
        "fullTemplateTypeCheck": true,
        "preserveWhitespaces": true,
                  ...
      }
    }
    ```

93. ### Làm thế nào để enable kiểm tra biểu thức binding?

    Bạn có thể enable kiểm tra biểu thức binding một cách rõ ràng bằng cách thêm tùy chọn compiler **fullTemplateTypeCheck** trong "angularCompilerOptions" của tsconfig.json của dự án. Nó tạo ra các thông báo lỗi khi một lỗi kiểu được phát hiện trong một biểu thức binding template.

    Ví dụ, xem xét component sau:

    ```typescript
    @Component({
      selector: "my-component",
      template: "{{user.contacts.email}}",
    })
    class MyComponent {
      user?: User;
    }
    ```

    Điều này sẽ tạo ra lỗi sau:

    ```typescript
    my.component.ts.MyComponent.html(1,1): : Property 'contacts' does not exist on type 'User'. Did you mean 'contact'?
    ```

94. ### Mục đích của hàm cast type any là gì?

    Bạn có thể tắt kiểm tra kiểu biểu thức binding bằng cách sử dụng hàm cast type $any() (bằng cách bao quanh biểu thức). Trong ví dụ sau, lỗi Property contacts does not exist bị chặn bằng cách cast user thành kiểu any.

    ```typescript
    template: "{{ $any(user).contacts.email }}";
    ```

    Hàm cast $any() cũng hoạt động với this để cho phép truy cập vào các thành viên chưa khai báo của component.

    ```typescript
    template: "{{ $any(this).contacts.email }}";
    ```

95. ### Toán tử non null type assertion là gì?

    Bạn có thể sử dụng toán tử non-null type assertion để chặn lỗi Object is possibly 'undefined'. Trong ví dụ sau, các thuộc tính user và contact luôn được đặt cùng nhau, ngụ ý rằng contact luôn non-null nếu user là non-null. Lỗi được chặn trong ví dụ bằng cách sử dụng contact!.email.

    ```typescript
    @Component({
      selector: "my-component",
      template:
        '<span *ngIf="user"> {{user.name}} contacted through {{contact!.email}} </span>',
    })
    class MyComponent {
      user?: User;
      contact?: Contact;

      setData(user: User, contact: Contact) {
        this.user = user;
        this.contact = contact;
      }
    }
    ```

96. ### Type narrowing là gì?

    Biểu thức được sử dụng trong directive ngIf được sử dụng để thu hẹp các union type trong Angular template compiler tương tự như biểu thức if trong typescript. Vì vậy \*ngIf cho phép trình biên dịch typeScript suy luận rằng dữ liệu được sử dụng trong biểu thức binding sẽ không bao giờ undefined.

    ```typescript
    @Component({
      selector: "my-component",
      template: '<span *ngIf="user"> {{user.contact.email}} </span>',
    })
    class MyComponent {
      user?: User;
    }
    ```

97. ### Làm thế nào để mô tả các dependencies khác nhau trong ứng dụng angular?

    Phần dependencies của package.json trong một ứng dụng angular có thể được chia như sau,

    1. **Angular packages:** Các package Angular core và các module tùy chọn; tên package của chúng bắt đầu bằng @angular/.
    2. **Support packages:** Các thư viện bên thứ ba phải có mặt để các ứng dụng Angular chạy.
    3. **Polyfill packages:** Polyfills lấp đầy các khoảng trống trong triển khai JavaScript của trình duyệt.

98. ### Zone là gì?

    Zone là một ngữ cảnh thực thi tồn tại qua các tác vụ bất đồng bộ. Angular dựa vào zone.js để chạy các quy trình phát hiện thay đổi của Angular khi các hoạt động JavaScript gốc phát ra sự kiện.

99. ### Mục đích của common module là gì?

    Các services, pipes và directives thường cần thiết được cung cấp bởi module @angular/common. Ngoài ra HttpClientModule có sẵn dưới @angular/common/http.

100.  ### Codelyzer là gì?
      Codelyzer cung cấp tập hợp các quy tắc tslint cho việc phân tích mã tĩnh của các dự án Angular TypeScript. Bạn có thể chạy trình phân tích mã tĩnh trên các ứng dụng web, NativeScript, Ionic v.v. Angular CLI có hỗ trợ cho điều này và nó có thể được sử dụng như dưới đây,
      ```bash
      ng new codelyzer
      ng lint
      ```

      101. ### Angular animation là gì?

     Hệ thống animation của Angular được xây dựng dựa trên chức năng CSS để animate bất kỳ thuộc tính nào mà trình duyệt coi là có thể animate. Các thuộc tính này bao gồm vị trí, kích thước, transforms, màu sắc, border v.v. Các module Angular cho animations là **@angular/animations** và **@angular/platform-browser** và các dependencies này được tự động thêm vào project của bạn khi bạn tạo project bằng Angular CLI.

102. ### Các bước để sử dụng module animation là gì?

     Bạn cần thực hiện các bước sau để triển khai animation trong project angular của mình,

     1. **Kích hoạt module animations:** Import BrowserAnimationsModule để thêm khả năng animation vào module ứng dụng root Angular của bạn (ví dụ, src/app/app.module.ts).

        ```typescript
        import { NgModule } from "@angular/core";
        import { BrowserModule } from "@angular/platform-browser";
        import { BrowserAnimationsModule } from "@angular/platform-browser/animations";

        @NgModule({
          imports: [BrowserModule, BrowserAnimationsModule],
          declarations: [],
          bootstrap: [],
        })
        export class AppModule {}
        ```

     2. **Import các hàm animation vào file component:** Import các hàm animation cần thiết từ @angular/animations trong các file component (ví dụ, src/app/app.component.ts).
        ```typescript
        import {
          trigger,
          state,
          style,
          animate,
          transition,
          // ...
        } from "@angular/animations";
        ```
     3. **Thêm thuộc tính metadata animation:** thêm một thuộc tính metadata có tên animations: trong decorator @Component() trong các file component (ví dụ, src/app/app.component.ts)
        ```typescript
        @Component({
          selector: 'app-root',
          templateUrl: 'app.component.html',
          styleUrls: ['app.component.css'],
          animations: [
            // các trigger animation đặt ở đây
          ]
        })
        ```

103. ### Hàm State là gì?

     Hàm state() của Angular được sử dụng để định nghĩa các trạng thái khác nhau để gọi ở cuối mỗi transition. Hàm này nhận hai tham số: một tên duy nhất như open hoặc closed và một hàm style().

     Ví dụ, bạn có thể viết một hàm state open

     ```typescript
     state('open', style({
       height: '300px',
       opacity: 0.5,
       backgroundColor: 'blue'
     })),
     ```

104. ### Hàm Style là gì?

     Hàm style được sử dụng để định nghĩa một tập hợp các styles để kết hợp với một tên trạng thái. Bạn cần sử dụng nó cùng với hàm state() để thiết lập các thuộc tính CSS style. Ví dụ, trong trạng thái close, nút có chiều cao 100 pixel, độ mờ 0.8, và màu nền xanh lá.

     ```typescript
     state('close', style({
       height: '100px',
       opacity: 0.8,
       backgroundColor: 'green'
     })),
     ```

     **Lưu ý:** Các thuộc tính style phải ở dạng camelCase.

105. ### Mục đích của hàm animate là gì?

     Angular Animations là một cách mạnh mẽ để triển khai các animation phức tạp và hấp dẫn cho ứng dụng web một trang Angular của bạn.

     ```typescript
     import { Component, OnInit, Input } from "@angular/core";
     import {
       trigger,
       state,
       style,
       animate,
       transition,
     } from "@angular/animations";

     @Component({
       selector: "app-animate",
       templateUrl: `<div [@changeState]="currentState" class="myblock mx-auto"></div>`,
       styleUrls: `.myblock {
         background-color: green;
         width: 300px;
         height: 250px;
         border-radius: 5px;
         margin: 5rem;
         }`,
       animations: [
         trigger("changeState", [
           state(
             "state1",
             style({
               backgroundColor: "green",
               transform: "scale(1)",
             })
           ),
           state(
             "state2",
             style({
               backgroundColor: "red",
               transform: "scale(1.5)",
             })
           ),
           transition("*=>state1", animate("300ms")),
           transition("*=>state2", animate("2000ms")),
         ]),
       ],
     })
     export class AnimateComponent implements OnInit {
       @Input() currentState;

       constructor() {}

       ngOnInit() {}
     }
     ```

106. ### Hàm transition là gì?

     Hàm transition trong animation được sử dụng để chỉ định các thay đổi xảy ra giữa hai trạng thái trong một khoảng thời gian. Nó chấp nhận hai tham số: tham số đầu tiên chấp nhận một biểu thức định nghĩa hướng giữa hai trạng thái transition, và tham số thứ hai chấp nhận một hàm animate().

     Hãy xem một ví dụ về transition trạng thái từ open sang closed với một transition nửa giây giữa các trạng thái.

     ```typescript
     transition('open => closed', [
       animate('500ms')
     ]),
     ```

107. ### Làm thế nào để inject script động trong angular?

     Sử dụng DomSanitizer chúng ta có thể inject động Html, Style, Script, Url.

     ```typescript
     import { Component, OnInit } from "@angular/core";
     import { DomSanitizer } from "@angular/platform-browser";
     @Component({
       selector: "my-app",
       template: ` <div [innerHtml]="htmlSnippet"></div> `,
     })
     export class App {
       constructor(protected sanitizer: DomSanitizer) {}
       htmlSnippet: string = this.sanitizer.bypassSecurityTrustScript(
         "<script>safeCode()</script>"
       );
     }
     ```

108. ### Service worker là gì và vai trò của nó trong Angular?

     Service worker là một script chạy trong trình duyệt web và quản lý việc cache cho một ứng dụng. Bắt đầu từ phiên bản 5.0.0, Angular đi kèm với một triển khai service worker. Angular service worker được thiết kế để tối ưu hóa trải nghiệm người dùng cuối khi sử dụng ứng dụng qua kết nối mạng chậm hoặc không ổn định, đồng thời cũng giảm thiểu rủi ro của việc phục vụ nội dung đã cũ.

109. ### Các mục tiêu thiết kế của service workers là gì?

     Dưới đây là danh sách các mục tiêu thiết kế của Angular's service workers,

     1. Nó cache một ứng dụng giống như cài đặt một ứng dụng gốc
     2. Một ứng dụng đang chạy tiếp tục chạy với cùng phiên bản của tất cả các file mà không có bất kỳ file không tương thích nào
     3. Khi bạn làm mới ứng dụng, nó tải phiên bản đã được cache đầy đủ mới nhất
     4. Khi các thay đổi được xuất bản thì nó ngay lập tức cập nhật trong nền
     5. Service workers tiết kiệm băng thông bằng cách chỉ tải xuống các tài nguyên khi chúng thay đổi.

110. ### Sự khác biệt giữa AngularJS và Angular liên quan đến dependency injection là gì?

     Dependency injection là một thành phần chung trong cả AngularJS và Angular, nhưng có một số khác biệt chính giữa hai framework về cách nó hoạt động.

     | AngularJS                                                | Angular                                                                                           |
     | -------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
     | Các token dependency injection luôn là strings           | Các token có thể có các kiểu khác nhau. Chúng thường là các class và đôi khi có thể là strings    |
     | Chỉ có một injector ngay cả khi là ứng dụng multi-module | Có một cây phân cấp các injector, với một root injector và một injector bổ sung cho mỗi component |

111. ### Angular Ivy là gì?

     Angular Ivy là một engine rendering mới cho Angular. Bạn có thể chọn sử dụng phiên bản preview của Ivy từ Angular phiên bản 8.

     1. Bạn có thể enable ivy trong một project mới bằng cách sử dụng flag --enable-ivy với lệnh ng new

        ```bash
        ng new ivy-demo-app --enable-ivy
        ```

     2. Bạn có thể thêm nó vào một project hiện có bằng cách thêm option `enableIvy` trong `angularCompilerOptions` trong file `tsconfig.app.json` của project.

        ```typescript
        {
          "compilerOptions": { ... },
          "angularCompilerOptions": {
            "enableIvy": true
          }
        }
        ```

112. ### Các tính năng được bao gồm trong ivy preview là gì?

     Bạn có thể mong đợi các tính năng dưới đây với Ivy preview,

     1. Mã được tạo ra dễ đọc và debug hơn tại runtime
     2. Thời gian rebuild nhanh hơn
     3. Cải thiện kích thước payload
     4. Cải thiện kiểm tra kiểu template

113. ### Tôi có thể sử dụng biên dịch AOT với Ivy không?

     Có, đây là một cấu hình được khuyến nghị. Ngoài ra, biên dịch AOT với Ivy nhanh hơn. Vì vậy bạn cần thiết lập các tùy chọn build mặc định (trong angular.json) cho project của bạn để luôn sử dụng biên dịch AOT.

     ```typescript
     {
       "projects": {
         "my-project": {
           "architect": {
             "build": {
               "options": {
                 ...
                 "aot": true,
               }
             }
           }
         }
       }
     }
     ```

114. ### Angular Language Service là gì?

     Angular Language Service là một cách để nhận được code completion, lỗi, gợi ý, và điều hướng bên trong các template Angular cho dù chúng ở bên ngoài trong một file HTML hoặc nhúng trong annotations/decorators trong một chuỗi. Nó có khả năng tự động phát hiện rằng bạn đang mở một file Angular, đọc file `tsconfig.json` của bạn, tìm tất cả các template bạn có trong ứng dụng, và sau đó cung cấp tất cả các dịch vụ ngôn ngữ.

115. ### Làm thế nào để cài đặt angular language service trong project?

     Bạn có thể cài đặt Angular Language Service trong project của bạn với lệnh npm sau,

     ```typescript
     npm install --save-dev @angular/language-service
     ```

     Sau đó thêm phần sau vào phần "compilerOptions" của tsconfig.json của project

     ```typescript
     "plugins": [
         {"name": "@angular/language-service"}
     ]
     ```

     **Lưu ý:** Các dịch vụ completion và diagnostic chỉ hoạt động cho các file .ts. Bạn cần sử dụng các plugin tùy chỉnh để hỗ trợ các file HTML.

116. ### Có hỗ trợ editor nào cho Angular Language Service không?

     Có, Angular Language Service hiện có sẵn cho các IDE Visual Studio Code và WebStorm. Bạn cần cài đặt angular language service bằng extension và devDependency tương ứng. Trong trình soạn thảo sublime, bạn cần cài đặt typescript có model plugin dịch vụ ngôn ngữ.

117. ### Giải thích các tính năng được cung cấp bởi Angular Language Service?

     Về cơ bản có 3 tính năng chính được cung cấp bởi Angular Language Service,

     1. **Autocompletion:** Autocompletion có thể tăng tốc thời gian phát triển của bạn bằng cách cung cấp cho bạn các khả năng và gợi ý theo ngữ cảnh khi bạn gõ trong phần interpolation và elements.

        ![ScreenShot](images/language-completion.gif)

     2. **Error checking:** Nó cũng có thể cảnh báo bạn về các lỗi trong code của bạn.

        ![ScreenShot](images/language-error.gif)

     3. **Navigation:** Navigation cho phép bạn di chuột qua một component, directive, module và sau đó click và nhấn F12 để đi trực tiếp đến định nghĩa của nó.

        ![ScreenShot](images/language-navigation.gif)

118. ### Làm thế nào để thêm web workers vào ứng dụng của bạn?

     Bạn có thể thêm web worker ở bất kỳ đâu trong ứng dụng của bạn. Ví dụ, Nếu file chứa tính toán phức tạp của bạn là `src/app/app.component.ts`, bạn có thể thêm một Web Worker bằng lệnh `ng generate web-worker app` sẽ tạo file web worker `src/app/app.worker.ts`. Lệnh này sẽ thực hiện các hành động dưới đây,

     1. Cấu hình project của bạn để sử dụng Web Workers
     2. Thêm app.worker.ts để nhận messages
        ```typescript
        addEventListener("message", ({ data }) => {
          const response = `worker response to ${data}`;
          postMessage(response);
        });
        ```
     3. File component `app.component.ts` được cập nhật với file web worker
        ```typescript
        if (typeof Worker !== "undefined") {
          // Tạo mới
          const worker = new Worker("./app.worker", { type: "module" });
          worker.onmessage = ({ data }) => {
            console.log("page got message: ${data}");
          };
          worker.postMessage("hello");
        } else {
          // Web Workers không được hỗ trợ trong môi trường này.
        }
        ```

     **Lưu ý:** Bạn có thể cần phải refactor lại code web worker ban đầu của bạn để gửi messages tới và từ.

119. ### Những hạn chế với web workers là gì?

     Bạn cần nhớ hai điều quan trọng khi sử dụng Web Workers trong các project Angular,

120. ### Class field decorators là gì?

     Class field decorators là các statement được khai báo ngay trước một trường trong định nghĩa class để định nghĩa kiểu của trường đó. Một số ví dụ là: @input và @output,

     ```typescript
     @Input() myProperty;
     @Output() myEvent = new EventEmitter();
     ```

121. ### Declarable là gì trong Angular?

     Declarable là một kiểu class mà bạn có thể thêm vào danh sách declarations của một NgModule. Các kiểu class như components, directives, và pipes có thể được khai báo trong module. Cấu trúc của declarations sẽ là,

     ```typescript
     declarations: [
       YourComponent,
       YourPipe,
       YourDirective
     ],
     ```

122. ### Những hạn chế đối với các class declarable là gì?

     Các class sau không nên được khai báo,

     1. Class đã được khai báo trong một NgModule khác
     2. Các class Ngmodule
     3. Các class Service
     4. Các class Helper

123. ### DI token là gì?

     DI token là một token tra cứu liên kết với một provider dependency trong hệ thống dependency injection. Injector duy trì một map token-provider nội bộ mà nó tham chiếu đến khi được yêu cầu một dependency và DI token là khóa cho map đó. Hãy xem ví dụ về việc sử dụng DI Token,

     ```typescript
     const BASE_URL = new InjectionToken() < string > "BaseUrl";
     const injector = Injector.create({
       providers: [{ provide: BASE_URL, useValue: "http://some-domain.com" }],
     });
     const url = injector.get(BASE_URL);
     ```

124. ### Angular DSL là gì?

     Domain-specific language (DSL) là một ngôn ngữ máy tính được chuyên biệt hóa cho một miền ứng dụng cụ thể. Angular có Domain Specific Language (DSL) riêng cho phép chúng ta viết cú pháp giống html trên HTML thông thường. Nó có compiler riêng biên dịch cú pháp này thành html mà trình duyệt có thể hiểu được. DSL này được định nghĩa trong các NgModules như animations, forms, và routing and navigation.

     Về cơ bản bạn sẽ thấy 3 cú pháp chính trong Angular DSL.

     1. `()`: Được sử dụng cho Output và sự kiện DOM.
     2. `[]`: Được sử dụng cho Input và các thuộc tính phần tử DOM cụ thể.
     3. `*`: Các directives cấu trúc (*ngFor hoặc *ngIf) sẽ ảnh hưởng/thay đổi cấu trúc DOM.

125. ### Subject RxJS trong Angular là gì?

     Subject RxJS là một loại Observable đặc biệt cho phép các giá trị được multicasted đến nhiều Observers. Trong khi Observable thông thường là unicast (mỗi Observer đã đăng ký sở hữu một quá trình thực thi độc lập của Observable), Subject là multicast.

     Subject giống như Observable, nhưng có thể multicast đến nhiều Observers. Subject giống như EventEmitters: chúng duy trì một registry của nhiều listeners.

     ```typescript
     import { Subject } from "rxjs";

     const subject = new Subject<number>();

     subject.subscribe({
       next: (v) => console.log(`observerA: ${v}`),
     });
     subject.subscribe({
       next: (v) => console.log(`observerB: ${v}`),
     });

     subject.next(1);
     subject.next(2);
     ```

126. ### Công cụ Bazel là gì?

     Bazel là một công cụ build mạnh mẽ được phát triển và sử dụng rộng rãi bởi Google và nó có thể theo dõi các dependencies giữa các package và build target khác nhau. Trong Angular8, bạn có thể build ứng dụng CLI của mình với Bazel.
     **Lưu ý:** Framework Angular tự nó được build với Bazel.

127. ### Những lợi ích của công cụ Bazel là gì?

     Dưới đây là danh sách các lợi ích chính của công cụ Bazel,

     1. Nó tạo khả năng build back-ends và front-ends của bạn với cùng một công cụ
     2. Build và test tăng dần
     3. Nó tạo khả năng có build từ xa và cache trên một build farm.

128. ### Làm thế nào để sử dụng Bazel với Angular CLI?

     Package @angular/bazel cung cấp một builder cho phép Angular CLI sử dụng Bazel như công cụ build.

     1. **Sử dụng trong một ứng dụng hiện có:** Thêm @angular/bazel bằng CLI
        ```bash
        ng add @angular/bazel
        ```
     2. **Sử dụng trong một ứng dụng mới:** Cài đặt package và tạo ứng dụng với tùy chọn collection
        ```bash
        npm install -g @angular/bazel
        ng new --collection=@angular/bazel
        ```
        Khi bạn sử dụng các lệnh ng build và ng serve, Bazel được sử dụng ngầm và xuất kết quả vào thư mục dist/bin.

129. ### Làm thế nào để chạy Bazel trực tiếp?

     Đôi khi bạn có thể muốn bỏ qua Angular CLI builder và chạy Bazel trực tiếp bằng Bazel CLI. Bạn có thể cài đặt nó toàn cục bằng package npm @bazel/bazel. i.e, Bazel CLI có sẵn dưới package @bazel/bazel. Sau đó bạn có thể áp dụng các lệnh phổ biến dưới đây,

     ```bash
     bazel build [targets] // Biên dịch các artifacts output mặc định của các targets đã cho.
     bazel test [targets] // Chạy các tests với các targets *_test được tìm thấy trong pattern.
     bazel run [target]: Biên dịch chương trình được biểu diễn bởi target và sau đó chạy nó.
     ```

130. ### Platform trong Angular là gì?

     Một platform là ngữ cảnh mà một ứng dụng Angular chạy trong đó. Platform phổ biến nhất cho các ứng dụng Angular là trình duyệt web, nhưng nó cũng có thể là một hệ điều hành cho thiết bị di động, hoặc một web server. Runtime-platform được cung cấp bởi các package @angular/platform-\* và các package này cho phép các ứng dụng sử dụng `@angular/core` và `@angular/common` thực thi trong các môi trường khác nhau.
     i.e, Angular có thể được sử dụng như framework độc lập với platform trong các môi trường khác nhau, Ví dụ,

     1. Khi chạy trong trình duyệt, nó sử dụng package `platform-browser`.
     2. Khi SSR(server-side rendering) được sử dụng, nó sử dụng package `platform-server` để cung cấp triển khai web server.

131. ### Điều gì xảy ra nếu tôi import cùng một module hai lần?

     Nếu nhiều modules import cùng một module thì angular đánh giá nó chỉ một lần (Khi nó gặp module lần đầu tiên). Nó tuân theo điều kiện này ngay cả khi module xuất hiện ở bất kỳ cấp độ nào trong phân cấp của các NgModules đã import.

132. ### Làm thế nào để chọn một phần tử trong template component?

     Bạn có thể sử dụng directive `@ViewChild` để truy cập các phần tử trong view trực tiếp. Hãy lấy phần tử input với một tham chiếu,

     ```html
     <input #uname />
     ```

     và định nghĩa view child directive và truy cập nó trong lifecycle hook ngAfterViewInit

     ```typescript
     @ViewChild('uname') input;

     ngAfterViewInit() {
       console.log(this.input.nativeElement.value);
     }
     ```

133. ### Làm thế nào để phát hiện route thay đổi trong Angular?

     Trong Angular7, bạn có thể subscribe vào router để phát hiện các thay đổi. Subscription cho các sự kiện router sẽ như sau,

     ```typescript
     this.router.events.subscribe((event: Event) => {});
     ```

     Hãy lấy một component đơn giản để phát hiện thay đổi router

     ```typescript
     import { Component } from "@angular/core";
     import {
       Router,
       Event,
       NavigationStart,
       NavigationEnd,
       NavigationError,
     } from "@angular/router";

     @Component({
       selector: "app-root",
       template: `<router-outlet></router-outlet>`,
     })
     export class AppComponent {
       constructor(private router: Router) {
         this.router.events.subscribe((event: Event) => {
           if (event instanceof NavigationStart) {
             // Hiển thị loading indicator và thực hiện một hành động
           }

           if (event instanceof NavigationEnd) {
             // Ẩn loading indicator và thực hiện một hành động
           }

           if (event instanceof NavigationError) {
             // Ẩn loading indicator và thực hiện một hành động
             console.log(event.error); // Nó logs một lỗi để debug
           }
         });
       }
     }
     ```

134. ### Làm thế nào để truyền headers cho HTTP client?

     Bạn có thể truyền trực tiếp object map cho http client hoặc tạo class HttpHeaders để cung cấp các headers.

     ```typescript
     constructor(private _http: HttpClient) {}
     this._http.get('someUrl',{
        headers: {'header1':'value1','header2':'value2'}
     });

     (hoặc)
     let headers = new HttpHeaders().set('header1', headerValue1); // tạo object header
     headers = headers.append('header2', headerValue2); // thêm một header mới, tạo một object mới
     headers = headers.append('header3', headerValue3); // thêm một header khác

     let params = new HttpParams().set('param1', value1); // tạo object params
     params = params.append('param2', value2); // thêm một param mới, tạo một object mới
     params = params.append('param3', value3); // thêm một param khác

     return this._http.get<any[]>('someUrl', { headers: headers, params: params })
     ```

135. ### Mục đích của differential loading trong CLI là gì?

     Từ phiên bản Angular8 trở đi, các ứng dụng được build sử dụng chiến lược differential loading từ CLI để build hai bundle riêng biệt như một phần của ứng dụng đã triển khai của bạn.

     1. Build đầu tiên chứa cú pháp ES2015 tận dụng sự hỗ trợ có sẵn trong các trình duyệt hiện đại, gửi ít polyfills hơn, và dẫn đến kích thước bundle nhỏ hơn.
     2. Build thứ hai chứa cú pháp ES5 cũ để hỗ trợ các trình duyệt cũ hơn với tất cả các polyfills cần thiết. Nhưng điều này dẫn đến kích thước bundle lớn hơn.

     **Lưu ý:** Chiến lược này được sử dụng để hỗ trợ nhiều trình duyệt nhưng nó chỉ tải code mà trình duyệt cần.

136. ### Angular có hỗ trợ dynamic imports không?

     Có, Angular 8 hỗ trợ dynamic imports trong cấu hình router. i.e, Bạn có thể sử dụng statement import cho lazy loading module bằng phương thức `loadChildren` và nó sẽ được hiểu bởi các IDEs(VSCode và WebStorm), webpack, v.v.
     Trước đây, bạn đã viết như dưới đây để lazy load feature module. Nếu bạn có lỗi chính tả trong tên module, nó vẫn chấp nhận chuỗi và ném ra lỗi trong thời gian build.

     ```typescript
     {path: 'user', loadChildren: './users/user.module#UserModulee'},
     ```

     Vấn đề này được giải quyết bằng cách sử dụng dynamic imports và IDEs có thể tìm thấy nó trong thời gian biên dịch.

     ```typescript
     {path: 'user', loadChildren: () => import('./users/user.module').then(m => m.UserModule)};
     ```

137. ### Lazy loading là gì?

     Lazy loading là một trong những khái niệm hữu ích nhất của Angular Routing. Nó giúp chúng ta tải các trang web theo từng phần thay vì tải tất cả trong một bundle lớn. Nó được sử dụng để lazy loading bằng cách tải feature module bất đồng bộ cho routing bất cứ khi nào cần thiết sử dụng thuộc tính `loadChildren`. Hãy tải cả hai feature module `Customer` và `Order` một cách lazy như dưới đây,

     ```typescript
     const routes: Routes = [
       {
         path: "customers",
         loadChildren: () =>
           import("./customers/customers.module").then(
             (module) => module.CustomersModule
           ),
       },
       {
         path: "orders",
         loadChildren: () =>
           import("./orders/orders.module").then(
             (module) => module.OrdersModule
           ),
       },
       {
         path: "",
         redirectTo: "",
         pathMatch: "full",
       },
     ];
     ```

138. ### Workspace APIs là gì?

     Angular 8.0 release giới thiệu Workspace APIs để giúp các nhà phát triển dễ dàng đọc và sửa đổi file angular.json thay vì sửa đổi nó một cách thủ công. Hiện tại, định dạng lưu trữ duy nhất được hỗ trợ là định dạng dựa trên JSON được sử dụng bởi Angular CLI. Bạn có thể enable hoặc thêm tùy chọn optimization cho build target như dưới đây,

     ```typescript
     import { NodeJsSyncHost } from "@angular-devkit/core/node";
     import { workspaces } from "@angular-devkit/core";

     async function addBuildTargetOption() {
       const host = workspaces.createWorkspaceHost(new NodeJsSyncHost());
       const workspace = await workspaces.readWorkspace(
         "path/to/workspace/directory/",
         host
       );

       const project = workspace.projects.get("my-app");
       if (!project) {
         throw new Error("my-app does not exist");
       }

       const buildTarget = project.targets.get("build");
       if (!buildTarget) {
         throw new Error("build target does not exist");
       }

       buildTarget.options.optimization = true;

       await workspaces.writeWorkspace(workspace, host);
     }

     addBuildTargetOption();
     ```

139. ### Làm thế nào để nâng cấp phiên bản angular?

     Việc nâng cấp Angular khá dễ dàng sử dụng lệnh `ng update` của Angular CLI như dưới đây. Ví dụ, nếu bạn nâng cấp từ Angular 7 lên 8 thì các imports lazy loading route của bạn sẽ được tự động chuyển đổi sang cú pháp import mới.

     ```bash
     $ ng update @angular/cli @angular/core
     ```

140. ### Angular Material là gì?

     Angular Material là một collection của các component Material Design cho framework Angular tuân theo Material Design spec. Bạn có thể áp dụng Material Design rất dễ dàng sử dụng Angular Material. Việc cài đặt có thể được thực hiện thông qua npm hoặc yarn,

     ```bash
     npm install --save @angular/material @angular/cdk @angular/animations
     (HOẶC)
     yarn add @angular/material @angular/cdk @angular/animations
     ```

     Nó hỗ trợ hai phiên bản mới nhất của tất cả các trình duyệt chính. Phiên bản mới nhất của Angular material là 8.1.1

141. ### Làm thế nào để nâng cấp location service của angularjs?

     Nếu bạn đang sử dụng service `$location` trong ứng dụng AngularJS cũ của bạn, bây giờ bạn có thể sử dụng `LocationUpgradeModule` (unified location service) để đưa các trách nhiệm của service `$location` sang service `Location` trong Angular. Hãy thêm module này vào `AppModule` như dưới đây,

     ```typescript
     // Các imports khác ...
     import { LocationUpgradeModule } from "@angular/common/upgrade";

     @NgModule({
       imports: [
         // Các imports NgModule khác...
         LocationUpgradeModule.config(),
       ],
     })
     export class AppModule {}
     ```

142. ### NgUpgrade là gì?

     NgUpgrade là một thư viện được tạo ra bởi team Angular, mà bạn có thể sử dụng trong ứng dụng của mình để mix và match các components và directives của AngularJS và Angular và kết nối các hệ thống dependency injection của AngularJS và Angular.

143. ### Làm thế nào để test ứng dụng Angular bằng CLI?

     Angular CLI tải về và cài đặt mọi thứ cần thiết với Jasmine Test framework. Bạn chỉ cần chạy `ng test` để xem kết quả test. Theo mặc định lệnh này build ứng dụng trong chế độ watch, và khởi chạy `Karma test runner`. Output của kết quả test sẽ như dưới đây,

     ```bash
     10% building modules 1/1 modules 0 active
     ...INFO [karma]: Karma v1.7.1 server started at http://0.0.0.0:9876/
     ...INFO [launcher]: Launching browser Chrome ...
     ...INFO [launcher]: Starting browser Chrome
     ...INFO [Chrome ...]: Connected on socket ...
     Chrome ...: Executed 3 of 3 SUCCESS (0.135 secs / 0.205 secs)
     ```

     **Lưu ý:** Một trình duyệt chrome cũng mở ra và hiển thị output test trong "Jasmine HTML Reporter".

144. ### Làm thế nào để sử dụng polyfills trong Angular application?

     Angular CLI cung cấp sự hỗ trợ chính thức cho polyfills. Khi bạn tạo một project mới với lệnh ng new, một file cấu hình `src/polyfills.ts` được tạo ra như một phần của thư mục project của bạn. File này bao gồm polyfills bắt buộc và nhiều polyfills tùy chọn dưới dạng các JavaScript import statements. Hãy phân loại polyfills,

     1. **Polyfills bắt buộc:** Các polyfills này được cài đặt tự động khi bạn tạo project của bạn với lệnh ng new và các import statements tương ứng được enable trong file 'src/polyfills.ts'.
     2. **Polyfills tùy chọn:** Bạn cần cài đặt package npm của nó và sau đó tạo import statement trong file 'src/polyfills.ts'.
        Ví dụ, trước tiên bạn cần cài đặt package npm dưới đây để thêm web animations (tùy chọn) polyfill.

        ```bash
        npm install --save web-animations-js
        ```

        và tạo import statement trong file polyfill.

        ```typescript
        import "web-animations-js";
        ```

     3. Một số môi trường hoặc nền tảng (như @angular/platform-server) được sử dụng trong Server-side Rendering, không hỗ trợ Web Workers. Trong trường hợp này bạn cần cung cấp một cơ chế fallback để thực hiện các tính toán để hoạt động trong các môi trường này.
     4. Chạy Angular trong web worker sử dụng `@angular/platform-webworker` chưa được hỗ trợ trong Angular CLI.

145. ### Angular CLI Builder là gì?

     Trong Angular8, CLI Builder API đã ổn định và có sẵn cho các nhà phát triển muốn tùy chỉnh `Angular CLI` bằng cách thêm hoặc sửa đổi các lệnh. Ví dụ, bạn có thể cung cấp một builder để thực hiện một nhiệm vụ hoàn toàn mới, hoặc để thay đổi công cụ bên thứ ba nào được sử dụng bởi một lệnh hiện có.

146. ### Builder là gì?

     Builder function là một hàm sử dụng `Architect API` để thực hiện một quá trình phức tạp như "build" hoặc "test". Code builder được định nghĩa trong một gói npm. Ví dụ, BrowserBuilder chạy một webpack build cho target trình duyệt và KarmaBuilder khởi động server Karma và chạy một webpack build cho unit tests.

147. ### Làm thế nào để gọi một builder?

     Lệnh Angular CLI `ng run` được sử dụng để gọi một builder với một cấu hình target cụ thể. File cấu hình workspace, `angular.json`, chứa các cấu hình mặc định cho các builders có sẵn.

148. ### Làm thế nào để tạo app shell trong Angular?

     App shell là một cách để render một phần của ứng dụng của bạn thông qua một route tại thời điểm build. Điều này hữu ích cho lần paint đầu tiên của ứng dụng của bạn xuất hiện nhanh chóng vì trình duyệt có thể render HTML và CSS tĩnh mà không cần khởi tạo JavaScript. Bạn có thể đạt được điều này bằng cách sử dụng Angular CLI tạo ra một app shell cho việc chạy phía server của ứng dụng của bạn.

     ```typescript
     ng generate appShell [options] (hoặc)
     ng g appShell [options]
     ```

149. ### Các kiểu case trong Angular là gì?

     Angular sử dụng các quy ước viết hoa để phân biệt tên của các kiểu khác nhau. Angular tuân theo danh sách các kiểu case dưới đây.

     1. **camelCase :** Các symbols, properties, methods, tên pipe, selector directive không phải component, hằng số sử dụng chữ thường cho chữ cái đầu tiên của item. Ví dụ, "selectedUser"
     2. **UpperCamelCase (hoặc PascalCase):** Tên class, bao gồm các class định nghĩa components, interfaces, NgModules, directives, và pipes sử dụng chữ hoa cho chữ cái đầu tiên của item.
     3. **dash-case (hoặc "kebab-case"):** Phần mô tả của tên file, selectors của component sử dụng dấu gạch ngang giữa các từ. Ví dụ, "app-user-list".
     4. **UPPER_UNDERSCORE_CASE:** Tất cả các hằng số sử dụng chữ in hoa được kết nối bằng dấu gạch dưới. Ví dụ, "NUMBER_OF_USERS".

150. ### Các class decorators trong Angular là gì?

     Class decorator là một decorator xuất hiện ngay trước định nghĩa class, khai báo class thuộc loại đã cho, và cung cấp metadata phù hợp với loại đó

     Danh sách các decorators sau đây thuộc class decorators,

     1. @Component()
     2. @Directive()
     3. @Pipe()
     4. @Injectable()
     5. @NgModule() 


     151. ### Những cách để kích hoạt phát hiện thay đổi trong Angular là gì?

     Bạn có thể inject ApplicationRef hoặc NgZone, hoặc ChangeDetectorRef vào component của bạn và áp dụng các phương thức cụ thể dưới đây để kích hoạt phát hiện thay đổi trong Angular. Có 3 cách có thể:

     1. **ApplicationRef.tick():** Gọi phương thức này để xử lý phát hiện thay đổi và các tác dụng phụ của nó một cách rõ ràng. Nó kiểm tra toàn bộ cây component.
     2. **NgZone.run(callback):** Nó đánh giá hàm callback bên trong Angular zone.
     3. **ChangeDetectorRef.detectChanges():** Nó chỉ phát hiện các components và các con của nó.

152. ### Sự khác biệt của các phiên bản Angular là gì?

     Có nhiều phiên bản khác nhau của framework Angular. Hãy xem các tính năng của tất cả các phiên bản khác nhau,

     1. **Angular 1:**
        - Angular 1 (AngularJS) là framework angular đầu tiên được phát hành vào năm 2010.
        - AngularJS không được xây dựng cho thiết bị di động.
        - Nó dựa trên controllers với kiến trúc MVC.
     2. **Angular 2:**
        - Angular 2 được phát hành vào năm 2016. Angular 2 là một bản viết lại hoàn toàn của phiên bản Angular1.
        - Các vấn đề về hiệu suất mà phiên bản Angular 1 có đã được giải quyết trong phiên bản Angular 2.
        - Angular 2 được xây dựng từ đầu cho thiết bị di động không giống phiên bản Angular 1.
        - Angular 2 dựa trên components.
     3. **Angular 3:**
        - Sau đây là các phiên bản package khác nhau trong Angular 2:
          - @angular/core v2.3.0
          - @angular/compiler v2.3.0
          - @angular/http v2.3.0
          - @angular/router v3.3.0
        - Package router đã được đánh version 3 nên để tránh nhầm lẫn đã chuyển sang phiên bản Angular 4 và bỏ qua phiên bản 3.
     4. **Angular 4:**
        - Kích thước file code được tạo bởi compiler trong chế độ AOT được giảm rất nhiều.
        - Với Angular 4 kích thước các bundle sản phẩm giảm hàng trăm KB.
        - Các tính năng animation được loại bỏ khỏi angular/core và tạo thành một package riêng.
        - Hỗ trợ Typescript 2.1 và 2.2.
        - Angular Universal
        - New HttpClient
     5. **Angular 5:**
        - Angular 5 làm cho angular nhanh hơn. Nó cải thiện thời gian tải và thời gian thực thi.
        - Đi kèm với build optimizer mới.
        - Hỗ trợ Typescript 2.5.
        - Service Worker
     6. **Angular 6:**
        - Nó được phát hành vào tháng 5 năm 2018.
        - Bao gồm Angular Command Line Interface (CLI), Component Development KIT (CDK), Angular Material Package, Angular Elements.
        - Sửa lỗi Service Worker.
        - i18n
        - Chế độ thử nghiệm cho Ivy.
        - RxJS 6.0
        - Tree Shaking
     7. **Angular 7:**
        - Nó được phát hành vào tháng 10 năm 2018.
        - TypeScript 3.1
        - RxJS 6.3
        - Angular CLI mới
        - Khả năng CLI Prompts cung cấp khả năng đặt câu hỏi cho người dùng trước khi họ chạy. Nó giống như một cuộc đối thoại tương tác giữa người dùng và CLI
        - Với khả năng CLI Prompts được cải thiện, nó giúp các nhà phát triển đưa ra quyết định. Các lệnh ng mới hỏi người dùng về routing và các loại kiểu CSS (SCSS) và ng add @angular/material hỏi về themes và cử chỉ hoặc animations.
     8. **Angular 8:**
        - Nó được phát hành vào tháng 5 năm 2019.
        - TypeScript 3.4
     9. **Angular 9:**
        - Nó được phát hành vào tháng 2 năm 2020.
        - TypeScript 3.7
        - Ivy được kích hoạt mặc định
     10. **Angular 10:**
         - Nó được phát hành vào tháng 6 năm 2020.
         - TypeScript 3.9
         - TSlib 2.0

153. ### Các nguyên tắc bảo mật trong angular là gì?

     Dưới đây là danh sách các nguyên tắc bảo mật trong angular,

     1. Bạn nên tránh sử dụng trực tiếp DOM APIs.
     2. Bạn nên kích hoạt Content Security Policy (CSP) và cấu hình web server của bạn để trả về các header CSP HTTP phù hợp.
     3. Bạn nên sử dụng compiler template offline.
     4. Bạn nên sử dụng bảo vệ XSS phía Server.
     5. Bạn nên sử dụng DOM Sanitizer.
     6. Bạn nên ngăn chặn các tấn công CSRF hoặc XSRF.

154. ### Lý do để loại bỏ Web Tracing Framework là gì?

     Angular đã hỗ trợ tích hợp với Web Tracing Framework (WTF) cho mục đích kiểm tra hiệu suất. Vì nó không được bảo trì tốt và thất bại trong phần lớn các ứng dụng, nên sự hỗ trợ đã bị loại bỏ trong các phiên bản mới nhất.

155. ### Lý do để loại bỏ các package web worker là gì?

     Cả `@angular/platform-webworker` và `@angular/platform-webworker-dynamic` đều chính thức bị loại bỏ, team Angular nhận ra rằng việc chạy ứng dụng Angular trên Web worker không phải là một thực hành tốt.

156. ### Làm thế nào để tìm phiên bản angular CLI?

     Angular CLI cung cấp phiên bản đã cài đặt của nó bằng các cách khác nhau sử dụng lệnh ng,

     ```bash
     ng v
     ng version
     ng -v
     ng --version
     ```

     và output sẽ như dưới đây,

     ```bash
     Angular CLI: 1.6.3
     Node: 8.11.3
     OS: darwin x64
     Angular:
     ...
     ```

157. ### Angular hỗ trợ trình duyệt nào?

     Angular hỗ trợ hầu hết các trình duyệt gần đây bao gồm cả trình duyệt desktop và di động. Từ Angular 13 trở đi, IE không còn được hỗ trợ.

     | Trình duyệt | Phiên bản                  |
     | ----------- | -------------------------- |
     | Chrome      | 2 phiên bản chính mới nhất |
     | Firefox     | 2 phiên bản chính mới nhất |
     | Edge        | 2 phiên bản chính mới nhất |
     | Safari      | 2 phiên bản chính mới nhất |
     | iOS         | 2 phiên bản chính mới nhất |
     | Android     | 2 phiên bản chính mới nhất |

158. ### Schematic là gì?

     Đây là một thư viện scaffolding định nghĩa cách tạo hoặc chuyển đổi một dự án lập trình bằng cách tạo, sửa đổi, refactoring, hoặc di chuyển các file và code. Nó định nghĩa các quy tắc hoạt động trên một hệ thống file ảo được gọi là tree.

159. ### Rule trong Schematics là gì?

     Trong thế giới schematics, đó là một hàm hoạt động trên một file tree để tạo, xóa, hoặc sửa đổi các file theo một cách cụ thể.

160. ### Schematics CLI là gì?

     Schematics đi kèm với công cụ dòng lệnh riêng được gọi là Schematics CLI. Nó được sử dụng để cài đặt schematics thực thi, mà bạn có thể sử dụng để tạo một collection schematics mới với một schematic được đặt tên ban đầu. Thư mục collection là một workspace cho schematics. Bạn cũng có thể sử dụng lệnh schematics để thêm một schematic mới vào một collection hiện có, hoặc mở rộng một schematic hiện có. Bạn có thể cài đặt Schematic CLI toàn cục như sau,

     ```bash
     npm install -g @angular-devkit/schematics-cli
     ```

161. ### Các thực hành tốt nhất cho bảo mật trong angular là gì?

     Dưới đây là các thực hành tốt nhất về bảo mật trong angular,

     1. Sử dụng các phiên bản thư viện Angular mới nhất
     2. Không sửa đổi bản copy Angular của bạn
     3. Tránh các API Angular được đánh dấu trong tài liệu là "Rủi ro bảo mật"

162. ### Model bảo mật của Angular để ngăn chặn các tấn công XSS là gì?

     Angular coi tất cả các giá trị là không đáng tin cậy theo mặc định. i.e, Angular sanitize và escape các giá trị không đáng tin cậy khi một giá trị được chèn vào DOM từ một template, thông qua property, attribute, style, class binding, hoặc interpolation.

163. ### Vai trò của template compiler trong việc ngăn chặn các tấn công XSS là gì?

     Template compiler offline ngăn chặn các lỗ hổng gây ra bởi template injection, và cải thiện đáng kể hiệu suất ứng dụng. Vì vậy nên sử dụng template compiler offline trong các triển khai sản phẩm mà không tạo template động nào.

164. ### Các context bảo mật khác nhau trong Angular là gì?

     Angular định nghĩa các context bảo mật sau đây cho sanitization,

     1. **HTML:** Được sử dụng khi giải thích một giá trị như HTML chẳng hạn như binding vào innerHtml.
     2. **Style:** Được sử dụng khi binding CSS vào thuộc tính style.
     3. **URL:** Được sử dụng cho các thuộc tính URL như `<a href>`.
     4. **Resource URL:** Là một URL sẽ được tải và thực thi như code chẳng hạn như `<script src>`.

165. ### Sanitization là gì? Angular có hỗ trợ nó không?

     **Sanitization** là việc kiểm tra một giá trị không đáng tin cậy, chuyển nó thành một giá trị an toàn để chèn vào DOM. Có, Angular hỗ trợ sanitization. Nó sanitize các giá trị không đáng tin cậy cho HTML, styles, và URLs nhưng việc sanitize resource URLs là không thể vì chúng chứa code tùy ý.

166. ### Mục đích của innerHTML là gì?

     innerHTML là một thuộc tính của HTML-Elements, cho phép bạn thiết lập nội dung html của nó theo cách lập trình. Hãy hiển thị đoạn code html dưới đây trong một thẻ `<div>` bằng cách sử dụng innerHTML binding,

     ```html
     <div [innerHTML]="htmlSnippet"></div>
     ```

     và định nghĩa thuộc tính htmlSnippet từ bất kỳ component nào

     ```typescript
     export class myComponent {
       htmlSnippet: string = "<b>Hello World</b>, Angular";
     }
     ```

     Không may là thuộc tính này có thể gây ra lỗi bảo mật Cross Site Scripting (XSS) khi xử lý không đúng cách.

167. ### Sự khác biệt giữa nội dung được nội suy và innerHTML là gì?

     Sự khác biệt chính giữa nội dung được nội suy và innerHTML là cách code được giải thích. Nội dung được nội suy luôn được escape i.e, HTML không được giải thích và trình duyệt hiển thị các dấu ngoặc nhọn trong nội dung văn bản của phần tử. Trong khi đó với innerHTML binding, nội dung được giải thích i.e, trình duyệt sẽ chuyển đổi các ký tự < và > thành HTMLEntities. Ví dụ, cách sử dụng trong template sẽ như sau,

     ```html
     <p>Interpolated value:</p>
     <div>{{htmlSnippet}}</div>
     <p>Binding of innerHTML:</p>
     <div [innerHTML]="htmlSnippet"></div>
     ```

     và thuộc tính được định nghĩa trong một component.

     ```typescript
     export class InnerHtmlBindingComponent {
       htmlSnippet =
         'Template <script>alert("XSS Attack")</script> <b>Code attached</b>';
     }
     ```

     Mặc dù innerHTML binding tạo ra cơ hội cho tấn công XSS, Angular nhận ra giá trị là không an toàn và tự động sanitize nó.

168. ### Làm thế nào để ngăn chặn sanitization tự động?

     Đôi khi các ứng dụng thực sự cần bao gồm code thực thi như hiển thị `<iframe>` từ một URL. Trong trường hợp này, bạn cần ngăn chặn sanitization tự động trong Angular bằng cách nói rằng bạn đã kiểm tra một giá trị, kiểm tra cách nó được tạo ra, và đảm bảo rằng nó sẽ luôn an toàn. Về cơ bản nó bao gồm 2 bước,

     1. Inject DomSanitizer: Bạn có thể inject DomSanitizer trong component như một tham số trong constructor
     2. Đánh dấu giá trị đáng tin cậy bằng cách gọi một trong các phương thức dưới đây

        1. bypassSecurityTrustHtml
        2. bypassSecurityTrustScript
        3. bypassSecurityTrustStyle
        4. bypassSecurityTrustUrl
        5. bypassSecurityTrustResourceUrl

     Ví dụ, việc sử dụng url nguy hiểm thành url đáng tin cậy sẽ như sau,

     ```typescript
     constructor(private sanitizer: DomSanitizer) {
       this.dangerousUrl = 'javascript:alert("XSS attack")';
       this.trustedUrl = sanitizer.bypassSecurityTrustUrl(this.dangerousUrl);
     ```

169. ### Có an toàn khi sử dụng các phương thức API DOM trực tiếp về mặt bảo mật không?

     Không, các API hoặc phương thức DOM tích hợp của trình duyệt không tự động bảo vệ bạn khỏi các lỗ hổng bảo mật. Trong trường hợp này được khuyến nghị sử dụng các templates Angular thay vì tương tác trực tiếp với DOM. Nếu không thể tránh khỏi thì sử dụng các hàm sanitization tích hợp của Angular.

170. ### DOM sanitizer là gì?

     `DomSanitizer` được sử dụng để giúp ngăn chặn các lỗi bảo mật Cross Site Scripting (XSS) bằng cách sanitize các giá trị để an toàn khi sử dụng trong các ngữ cảnh DOM khác nhau.

171. ### Làm thế nào để hỗ trợ bảo vệ XSS phía server trong ứng dụng Angular?

     Bảo vệ XSS phía server được hỗ trợ trong ứng dụng angular bằng cách sử dụng một ngôn ngữ template tự động escape các giá trị để ngăn chặn các lỗ hổng XSS trên server. Nhưng đừng sử dụng ngôn ngữ template để tạo templates Angular trên server side vì nó tạo ra rủi ro cao về các lỗ hổng template-injection.

172. ### Angular có ngăn chặn các lỗ hổng cấp HTTP không?

     Angular có hỗ trợ tích hợp để ngăn chặn các lỗ hổng cấp http như cross-site request forgery (CSRF hoặc XSRF) và cross-site script inclusion (XSSI). Mặc dù các lỗ hổng này cần được giảm thiểu trên server-side, Angular cung cấp các helpers để làm cho việc tích hợp dễ dàng hơn trên client side.

     1. HttpClient hỗ trợ cơ chế token được sử dụng để ngăn chặn các tấn công XSRF
     2. Thư viện HttpClient nhận ra quy ước về các phản hồi JSON được thêm tiền tố (không thực thi js code với ")]}',\\n" ký tự) và tự động loại bỏ chuỗi ")]}',\\n" khỏi tất cả các phản hồi trước khi phân tích thêm

173. ### Http Interceptors là gì?

     Http Interceptors là một phần của @angular/common/http, kiểm tra và chuyển đổi các HTTP requests từ ứng dụng của bạn đến server và ngược lại trên HTTP responses. Các interceptors này có thể thực hiện nhiều nhiệm vụ ngầm, từ authentication đến logging.

     Cú pháp của interface HttpInterceptor trông như sau,

     ```typescript
     interface HttpInterceptor {
       intercept(
         req: HttpRequest<any>,
         next: HttpHandler
       ): Observable<HttpEvent<any>>;
     }
     ```

     Bạn có thể sử dụng interceptors bằng cách khai báo một class service triển khai phương thức intercept() của interface HttpInterceptor.

     ```typescript
     @Injectable()
     export class MyInterceptor implements HttpInterceptor {
         constructor() {}
         intercept(req: HttpRequest<any>, next: HttpHandler): Observable<HttpEvent<any>> {
             ...
         }
     }
     ```

     Sau đó bạn có thể sử dụng nó trong module của bạn,

     ```typescript
     @NgModule({
         ...
         providers: [
             {
                 provide: HTTP_INTERCEPTORS,
                 useClass: MyInterceptor,
                 multi: true
             }
         ]
         ...
     })
     export class AppModule {}
     ```

174. ### Các ứng dụng của HTTP interceptors là gì?

     HTTP Interceptors có thể được sử dụng cho các nhiệm vụ khác nhau,

     1. Authentication
     2. Logging
     3. Caching
     4. Fake backend
     5. URL transformation
     6. Modifying headers

175. ### Có hỗ trợ nhiều interceptor trong Angular không?

     Có, Angular hỗ trợ nhiều interceptor cùng một lúc. Bạn có thể định nghĩa nhiều interceptors trong thuộc tính providers:

     ```typescript
     providers: [
       { provide: HTTP_INTERCEPTORS, useClass: MyFirstInterceptor, multi: true },
       { provide: HTTP_INTERCEPTORS, useClass: MySecondInterceptor, multi: true }
     ],
     ```

     Các interceptors sẽ được gọi theo thứ tự chúng được cung cấp. i.e, MyFirstInterceptor sẽ được gọi đầu tiên trong cấu hình interceptors trên.

176. ### Làm thế nào để sử dụng interceptor cho toàn bộ ứng dụng?

     Bạn có thể sử dụng cùng một instance của `HttpInterceptors` cho toàn bộ ứng dụng bằng cách chỉ import `HttpClientModule` trong AppModule của bạn, và thêm các interceptors vào root application injector.
     Ví dụ, hãy định nghĩa một class có thể inject trong root application.

     ```typescript
     @Injectable()
     export class MyInterceptor implements HttpInterceptor {
       intercept(
         req: HttpRequest<any>,
         next: HttpHandler
       ): Observable<HttpEvent<any>> {
         return next.handle(req).do((event) => {
           if (event instanceof HttpResponse) {
             // Code goes here
           }
         });
       }
     }
     ```

     Sau đó import HttpClientModule trong AppModule

     ```typescript
     @NgModule({
       declarations: [AppComponent],
       imports: [BrowserModule, HttpClientModule],
       providers: [
         { provide: HTTP_INTERCEPTORS, useClass: MyInterceptor, multi: true },
       ],
       bootstrap: [AppComponent],
     })
     export class AppModule {}
     ```

177. ### Làm thế nào Angular đơn giản hóa Internationalization?

     Angular đơn giản hóa các lĩnh vực internationalization sau đây,

     1. Hiển thị ngày tháng, số, phần trăm và tiền tệ theo định dạng local.
     2. Chuẩn bị văn bản trong templates component để dịch.
     3. Xử lý các dạng số nhiều của từ.
     4. Xử lý văn bản thay thế.

178. ### Làm thế nào để đăng ký locale data thủ công?

     Theo mặc định, Angular chỉ chứa locale data cho en-US là tiếng Anh được sử dụng ở Hợp chủng quốc Hoa Kỳ. Nhưng nếu bạn muốn đặt sang locale khác, bạn phải import locale data cho locale mới đó. Sau đó bạn có thể đăng ký bằng phương thức `registerLocaleData` và cú pháp của phương thức này trông như sau,

     ```typescript
     registerLocaleData(data: any, localeId?: any, extraData?: any): void
     ```

     Ví dụ, hãy import locale tiếng Đức và đăng ký nó trong ứng dụng

     ```typescript
     import { registerLocaleData } from "@angular/common";
     import localeDe from "@angular/common/locales/de";

     registerLocaleData(localeDe, "de");
     ```

179. ### Bốn giai đoạn của dịch template là gì?

     Quá trình dịch template i18n có bốn giai đoạn:

     1. **Đánh dấu các thông điệp văn bản tĩnh trong templates component của bạn để dịch:** Bạn có thể đặt i18n trên mỗi thẻ element có văn bản cố định cần được dịch. Ví dụ, bạn cần thuộc tính i18n cho heading như dưới đây,

        ```html
        <h1 i18n>Hello i18n!</h1>
        ```

     2. **Tạo một file dịch:** Sử dụng lệnh Angular CLI xi18n để trích xuất văn bản đã đánh dấu vào một file nguồn dịch theo chuẩn công nghiệp. i.e, Mở cửa sổ terminal tại thư mục gốc của dự án ứng dụng và chạy lệnh CLI xi18n.

        ```bash
        ng xi18n
        ```

        Lệnh trên tạo một file có tên là `messages.xlf` trong thư mục gốc dự án của bạn.

        **Lưu ý:** Bạn có thể cung cấp các tùy chọn lệnh để thay đổi định dạng, tên, vị trí và locale nguồn của file được trích xuất.

     3. **Chỉnh sửa file dịch đã tạo:** Dịch văn bản đã trích xuất sang ngôn ngữ đích. Trong bước này, tạo một thư mục localization (như là `locale`) dưới thư mục gốc (src) và sau đó tạo file dịch ngôn ngữ đích bằng cách sao chép và đổi tên file messages.xlf mặc định. Bạn cần sao chép node văn bản nguồn và cung cấp bản dịch dưới thẻ target.
        Ví dụ, tạo file dịch (messages.de.xlf) cho ngôn ngữ Đức

        ```html
        <trans-unit id="greetingHeader" datatype="html">
          <source>Hello i18n!</source>
          <target>Hallo i18n !</target>
          <note priority="1" from="description">
            A welcome header for this sample
          </note>
          <note priority="1" from="meaning">
            welcome message
          </note>
        </trans-unit>
        ```

     4. **Hợp nhất file dịch đã hoàn thành vào ứng dụng:** Bạn cần sử dụng lệnh build của Angular CLI để biên dịch ứng dụng, chọn một cấu hình đặc thù cho locale, hoặc chỉ định các tùy chọn lệnh sau.

        1. --i18nFile=đường dẫn đến file dịch
        2. --i18nFormat=định dạng của file dịch
        3. --i18nLocale= locale id

180. ### Mục đích của thuộc tính i18n là gì?

     Thuộc tính i18n của Angular đánh dấu nội dung có thể dịch được. Nó là một thuộc tính tùy chỉnh, được nhận biết bởi các công cụ và trình biên dịch Angular. Trình biên dịch loại bỏ nó sau khi dịch.

     **Lưu ý:** Nhớ rằng i18n không phải là một directive Angular.

181. ### Mục đích của custom id là gì?

     Khi bạn thay đổi văn bản có thể dịch được, công cụ trích xuất Angular tạo một id mới cho đơn vị dịch đó. Vì hành vi này, bạn phải cập nhật file dịch với id mới mỗi lần.

     Ví dụ, file dịch `messages.de.xlf.html` đã tạo trans-unit cho một số thông điệp văn bản như dưới đây

     ```html
     <trans-unit
       id="827wwe104d3d69bf669f823jjde888"
       datatype="html"
     ></trans-unit>
     ```

     Bạn có thể tránh việc cập nhật thủ công thuộc tính `id` bằng cách chỉ định một custom id trong thuộc tính i18n bằng cách sử dụng tiền tố @@.

     ```html
     <h1 i18n="@@welcomeHeader">Hello i18n!</h1>
     ```

182. ### Điều gì xảy ra nếu custom id không duy nhất?

     Bạn cần định nghĩa custom ids là duy nhất. Nếu bạn sử dụng cùng một id cho hai thông điệp văn bản khác nhau thì chỉ cái đầu tiên được trích xuất. Nhưng bản dịch của nó được sử dụng thay thế cho cả hai thông điệp văn bản gốc.

     Ví dụ, hãy định nghĩa cùng custom id `myCustomId` cho hai thông điệp,

     ```html
     <h2 i18n="@@myCustomId">Good morning</h3>
     <!-- ... -->
     <h2 i18n="@@myCustomId">Good night</p>
     ```

     và đơn vị dịch được tạo cho văn bản đầu tiên cho ngôn ngữ Đức như

     ```html
     <trans-unit id="myId" datatype="html">
       <source>Good morning</source>
       <target state="new">Guten Morgen</target>
     </trans-unit>
     ```

     Vì custom id là giống nhau, cả hai phần tử trong bản dịch chứa cùng văn bản như dưới đây

     ```html
     <h2>Guten Morgen</h2>
     <h2>Guten Morgen</h2>
     ```

183. ### Tôi có thể dịch văn bản mà không cần tạo một phần tử không?

     Có, bạn có thể đạt được điều này bằng cách sử dụng thuộc tính `<ng-container>`. Thông thường bạn cần bọc một nội dung văn bản với thuộc tính i18n để dịch. Nhưng nếu bạn không muốn tạo một phần tử DOM mới chỉ để dịch, bạn có thể bọc văn bản trong một phần tử <ng-container>.

     ```html
     <ng-container i18n
       >I'm not using any DOM element for translation</ng-container
     >
     ```

     Nhớ rằng `<ng-container>` được chuyển đổi thành một comment html

184. ### Làm thế nào để dịch thuộc tính?

     Bạn có thể dịch các thuộc tính bằng cách đính kèm thuộc tính `i18n-x` trong đó x là tên của thuộc tính cần dịch. Ví dụ, bạn có thể dịch thuộc tính title của image như dưới đây,

     ```html
     <img [src]="example" i18n-title title="Internationalization" />
     ```

     Bên cạnh đó, bạn cũng có thể gán meaning, description và id với cú pháp i18n-x="<meaning>|<description>@@<id>".

185. ### Liệt kê các danh mục số nhiều?

     Số nhiều có các danh mục dưới đây tùy thuộc vào ngôn ngữ.

     1. =0 (hoặc bất kỳ số nào khác)
     2. zero
     3. one
     4. two
     5. few
     6. many
     7. other

186. ### Biểu thức ICU select là gì?

     Biểu thức ICU tương tự như các biểu thức số nhiều ngoại trừ việc bạn chọn giữa các bản dịch thay thế dựa trên một giá trị chuỗi thay vì một số. Ở đây bạn định nghĩa các giá trị chuỗi đó.

     Hãy xem binding component với thuộc tính `residenceStatus` có các giá trị có thể là "citizen", "permanent resident" và "foreigner" và thông điệp ánh xạ các giá trị đó với các bản dịch thích hợp.

     ```html
     <span i18n
       >The person is {residenceStatus, select, citizen {citizen} permanent
       resident {permanentResident} foreigner {foreigner}}</span
     >
     ```

187. ### Làm thế nào để báo cáo bản dịch bị thiếu?

     Theo mặc định, khi bản dịch bị thiếu, nó tạo ra một thông báo cảnh báo như "Missing translation for message 'somekey'". Nhưng bạn có thể cấu hình với một mức thông báo khác trong trình biên dịch Angular như dưới đây,

     1. **Error:** Nó ném ra một lỗi. Nếu bạn đang sử dụng biên dịch AOT, việc build sẽ thất bại. Nhưng nếu bạn đang sử dụng biên dịch JIT, ứng dụng sẽ không thể tải.
     2. **Warning (mặc định):** Nó hiển thị một cảnh báo 'Missing translation' trong console hoặc shell.
     3. **Ignore:** Nó không làm gì cả.

     Nếu bạn sử dụng trình biên dịch AOT thì bạn cần thực hiện các thay đổi trong phần `configurations` của file cấu hình Angular CLI của bạn, angular.json.

     ```typescript
     "configurations": {
       ...
       "de": {
         ...
         "i18nMissingTranslation": "error"
       }
     }
     ```

     Nếu bạn sử dụng trình biên dịch JIT, chỉ định mức cảnh báo trong cấu hình compiler tại bootstrap bằng cách thêm thuộc tính 'MissingTranslationStrategy' như dưới đây,

     ```typescript
     import { MissingTranslationStrategy } from "@angular/core";
     import { platformBrowserDynamic } from "@angular/platform-browser-dynamic";
     import { AppModule } from "./app/app.module";

     platformBrowserDynamic().bootstrapModule(AppModule, {
       missingTranslation: MissingTranslationStrategy.Error,
       providers: [
         // ...
       ],
     });
     ```

188. ### Làm thế nào để cung cấp cấu hình build cho nhiều locales?

     Bạn có thể cung cấp cấu hình build như đường dẫn file dịch, tên, định dạng và url ứng dụng trong cài đặt `configuration` của file Angular.json. Ví dụ, phiên bản tiếng Đức của ứng dụng của bạn cấu hình build như sau,

     ```typescript
     "configurations": {
       "de": {
         "aot": true,
         "outputPath": "dist/my-project-de/",
         "baseHref": "/fr/",
         "i18nFile": "src/locale/messages.de.xlf",
         "i18nFormat": "xlf",
         "i18nLocale": "de",
         "i18nMissingTranslation": "error",
       }
     ```

189. ### Thư viện angular là gì?

     Một thư viện Angular là một dự án Angular khác với một ứng dụng ở chỗ nó không thể chạy độc lập. Nó phải được import và sử dụng trong một ứng dụng. Ví dụ, bạn có thể import hoặc thêm thư viện `service worker` vào một ứng dụng Angular để biến một ứng dụng thành Progressive Web App (PWA).

     **Lưu ý:** Bạn có thể tạo thư viện bên thứ ba của riêng mình và xuất bản nó như một package npm để được sử dụng trong một Ứng dụng.

190. ### AOT compiler là gì?

     AOT compiler là một phần của quá trình build tạo ra một package ứng dụng nhỏ, nhanh, sẵn sàng chạy, thường dùng cho sản phẩm. Nó chuyển đổi code HTML và TypeScript Angular của bạn thành code JavaScript hiệu quả trong giai đoạn build trước khi trình duyệt tải xuống và chạy code đó.

191. ### Làm thế nào để chọn một phần tử trong template component?

     Bạn có thể điều khiển bất kỳ phần tử DOM nào thông qua ElementRef bằng cách inject nó vào constructor của component của bạn. i.e, Component nên có constructor với tham số ElementRef,

     ```typescript
     constructor(myElement: ElementRef) {
        el.nativeElement.style.backgroundColor = 'yellow';
     }
     ```

192. ### TestBed là gì?

     TestBed là một api để viết unit tests cho các ứng dụng và thư viện Angular. Mặc dù chúng ta vẫn viết tests trong Jasmine và chạy bằng Karma, API này cung cấp một cách dễ dàng hơn để tạo components, xử lý injection, test hành vi bất đồng bộ và tương tác với ứng dụng của chúng ta.

193. ### Protractor là gì?

     Protractor là một framework test end-to-end cho các ứng dụng Angular và AngularJS. Nó chạy các tests với ứng dụng của bạn đang chạy trong một trình duyệt thực, tương tác với nó như một người dùng thực sự.

     ```bash
     npm install -g protractor
     ```

194. ### Collection là gì?

     Collection là một tập hợp các schematics liên quan được thu thập trong một package npm. Ví dụ, collection `@schematics/angular` được sử dụng trong Angular CLI để áp dụng các transforms cho một dự án web-app. Bạn có thể tạo collection schematic của riêng mình để tùy chỉnh các dự án angular.

195. ### Làm thế nào để tạo schematics cho thư viện?

     Bạn có thể tạo các collection schematic của riêng mình để tích hợp thư viện của bạn với Angular CLI. Các collections này được phân loại thành 3 schematics chính,

     1. **Add schematics:** Các schematics này được sử dụng để cài đặt thư viện trong một Angular workspace bằng lệnh `ng add`.
        Ví dụ, schematic @angular/material cho phép lệnh add cài đặt và thiết lập Angular Material và theming.
     2. **Generate schematics**: Các schematics này được sử dụng để sửa đổi dự án, thêm cấu hình và scripts, và scaffolding artifacts trong thư viện bằng lệnh `ng generate`.
        Ví dụ, schematic generation của @angular/material cung cấp các schematics generation cho các component UI. Ví dụ component table được tạo bằng `ng generate @angular/material:table`.
     3. **Update schematics:** Các schematics này được sử dụng để cập nhật dependencies của thư viện và điều chỉnh cho các thay đổi breaking trong một phiên bản thư viện mới bằng lệnh `ng update`.
        Ví dụ, schematic update của @angular/material cập nhật các dependencies material và cdk bằng lệnh `ng update @angular/material`.

196. ### Làm thế nào để sử dụng jquery trong Angular?

     Bạn có thể sử dụng jquery trong Angular bằng 3 bước đơn giản,

     1. **Cài đặt dependency:** Đầu tiên, cài đặt dependency jquery bằng npm
        ```bash
           npm install --save jquery
        ```
     2. **Thêm script jquery:** Trong dự án Angular-CLI, thêm đường dẫn tương đối đến jquery trong file angular.json.
        ```typescript
        "scripts": [
           "node_modules/jquery/dist/jquery.min.js"
        ]
        ```
     3. **Bắt đầu sử dụng jquery:** Định nghĩa phần tử trong template. Trong khi đó khai báo biến jquery và áp dụng các class CSS lên phần tử.

        ```html
        <div id="elementId">
          <h1>JQuery integration</h1>
        </div>
        ```

        ```typescript
        import { Component, OnInit } from "@angular/core";

        declare var $: any; // (hoặc) import * as $ from 'jquery';

        @Component({
          selector: "app-root",
          templateUrl: "./app.component.html",
          styleUrls: ["./app.component.css"],
        })
        export class AppComponent implements OnInit {
          ngOnInit(): void {
            $(document).ready(() => {
              $("#elementId").css({
                "text-color": "blue",
                "font-size": "150%",
              });
            });
          }
        }
        ```

197. ### Lý do cho ngoại lệ No provider for HTTP là gì?

     Ngoại lệ này là do thiếu HttpClientModule trong module của bạn. Bạn chỉ cần import nó trong module như dưới đây,

     ```typescript
     import { HttpClientModule } from "@angular/common/http";

     @NgModule({
       imports: [BrowserModule, HttpClientModule],
       declarations: [AppComponent],
       bootstrap: [AppComponent],
     })
     export class AppModule {}
     ```

198. ### Router state là gì?

     RouterState là một interface đại diện cho trạng thái của router như một cây các routes đã kích hoạt.

     ```typescript
     interface RouterState extends Tree {
       snapshot: RouterStateSnapshot;
       toString(): string;
     }
     ```

     Bạn có thể truy cập RouterState hiện tại từ bất kỳ đâu trong ứng dụng Angular bằng service Router và thuộc tính routerState.

199. ### Làm thế nào để sử dụng SASS trong dự án angular?

     Khi bạn đang tạo dự án của mình với angular cli, bạn có thể sử dụng lệnh `ng new`. Nó tạo tất cả các components của bạn với các file sass được định nghĩa trước.

     ```bash
     ng new My_New_Project --style=sass
     ```

     Nhưng nếu bạn đang thay đổi style hiện có trong dự án của bạn thì sử dụng lệnh `ng set`,

     ```bash
     ng set defaults.styleExt scss
     ```

200. ### Mục đích của thuộc tính hidden là gì?

     Thuộc tính hidden được sử dụng để hiển thị hoặc ẩn phần tử DOM liên kết, dựa trên một biểu thức. Nó có thể được so sánh gần giống với directive `ng-show` trong AngularJS. Ví dụ, bạn muốn hiển thị tên người dùng dựa trên sự có sẵn của user bằng thuộc tính `hidden`.

     ```html
     <div [hidden]="!user.name">My name is: {{user.name}}</div>
     ```  

     201. ### Sự khác biệt giữa ngIf và thuộc tính hidden là gì?

     Sự khác biệt chính là \*ngIf sẽ xóa phần tử khỏi DOM, trong khi [hidden] thực sự chỉ thay đổi CSS style bằng cách đặt `display:none`. Nói chung việc thêm và xóa phần tử khỏi DOM cho các hành động thường xuyên là tốn kém.

202. ### Pipe slice là gì?

     Pipe slice được sử dụng để tạo một Array hoặc String mới chứa một tập con (slice) của các phần tử. Cú pháp trông như sau,

     ```typescript
     {{ value_expression | slice : start [ : end ] }}
     ```

     Ví dụ, bạn có thể cung cấp danh sách 'hello' dựa trên một mảng greeting,

     ```typescript
     @Component({
       selector: "list-pipe",
       template: `<ul>
         <li *ngFor="let i of greeting | slice : 0 : 5">{{ i }}</li>
       </ul>`,
     })
     export class PipeListComponent {
       greeting: string[] = [
         "h",
         "e",
         "l",
         "l",
         "o",
         "m",
         "o",
         "r",
         "n",
         "i",
         "n",
         "g",
       ];
     }
     ```

203. ### Thuộc tính index trong directive ngFor là gì?

     Thuộc tính index của directive NgFor được sử dụng để trả về index dựa trên 0 của item trong mỗi lần lặp. Bạn có thể capture index trong một biến input template và sử dụng nó trong template.

     Ví dụ, bạn có thể capture index trong một biến có tên indexVar và hiển thị nó với tên của todo sử dụng directive ngFor như sau.

     ```html
     <div *ngFor="let todo of todos; let i=index">
       {{i + 1}} - {{todo.name}}
     </div>
     ```

204. ### Mục đích của ngFor trackBy là gì?

     Mục đích chính của việc sử dụng \*ngFor với tùy chọn trackBy là tối ưu hóa hiệu suất. Thông thường nếu bạn sử dụng NgFor với tập dữ liệu lớn, một thay đổi nhỏ cho một item bằng cách xóa hoặc thêm một item, có thể kích hoạt một chuỗi thao tác DOM. Trong trường hợp này, Angular chỉ thấy một danh sách tham chiếu đối tượng mới và thay thế các phần tử DOM cũ bằng tất cả các phần tử DOM mới. Bạn có thể giúp Angular theo dõi những items nào được thêm hoặc xóa bằng cách cung cấp một hàm `trackBy` nhận vào index và item hiện tại làm tham số và cần trả về định danh duy nhất cho item này.

     Ví dụ, hãy đặt trackBy là phương thức trackByTodos()

     ```html
     <div *ngFor="let todo of todos; trackBy: trackByTodos">
       ({{todo.id}}) {{todo.name}}
     </div>
     ```

     và định nghĩa phương thức trackByTodos,

     ```typescript
     trackByTodos(index: number, item: Todo): number { return todo.id; }
     ```

205. ### Mục đích của directive ngSwitch là gì?

     Directive **NgSwitch** tương tự như câu lệnh switch trong JavaScript, hiển thị một phần tử từ nhiều phần tử có thể, dựa trên điều kiện switch. Trong trường hợp này chỉ phần tử được chọn được đưa vào DOM. Nó được sử dụng cùng với các directives `NgSwitch`, `NgSwitchCase` và `NgSwitchDefault`.

     Ví dụ, hãy hiển thị chi tiết trình duyệt dựa trên trình duyệt được chọn bằng directive ngSwitch.

     ```html
     <div [ngSwitch]="currentBrowser.name">
       <chrome-browser
         *ngSwitchCase="'chrome'"
         [item]="currentBrowser"
       ></chrome-browser>
       <firefox-browser
         *ngSwitchCase="'firefox'"
         [item]="currentBrowser"
       ></firefox-browser>
       <opera-browser
         *ngSwitchCase="'opera'"
         [item]="currentBrowser"
       ></opera-browser>
       <safari-browser
         *ngSwitchCase="'safari'"
         [item]="currentBrowser"
       ></safari-browser>
       <ie-browser *ngSwitchDefault [item]="currentItem"></ie-browser>
     </div>
     ```

206. ### Có thể đặt alias cho inputs và outputs không?

     Có, có thể đặt alias cho inputs và outputs theo hai cách.

     1. **Đặt alias trong metadata:** Inputs và outputs trong metadata được đặt alias bằng chuỗi phân cách bằng dấu hai chấm (:) với tên thuộc tính directive ở bên trái và alias công khai ở bên phải. i.e. Nó sẽ ở định dạng propertyName:alias.
        ```typescript
        inputs: ['input1: buyItem'],
        outputs: ['outputEvent1: completedEvent']
        ```
     2. **Đặt alias với decorator @Input()/@Output():** Alias có thể được chỉ định cho tên thuộc tính bằng cách truyền tên alias vào decorator @Input()/@Output(). i.e. Nó sẽ ở dạng @Input(alias) hoặc @Output(alias).
        ```typescript
        @Input('buyItem') input1: string;
        @Output('completedEvent') outputEvent1 = new EventEmitter<string>();
        ```

207. ### Safe navigation operator là gì?

     Safe navigation operator (?) (hoặc được gọi là Elvis Operator) được sử dụng để bảo vệ khỏi các giá trị `null` và `undefined` trong đường dẫn thuộc tính khi bạn không biết liệu đường dẫn có tồn tại hay không. i.e. Nó trả về giá trị của đường dẫn đối tượng nếu nó tồn tại, nếu không trả về giá trị null.

     Ví dụ, bạn có thể truy cập các thuộc tính lồng nhau của user profile một cách dễ dàng mà không gặp lỗi tham chiếu null như sau,

     ```html
     <p>The user firstName is: {{user?.fullName.firstName}}</p>
     ```

     Sử dụng safe navigation operator này, framework Angular dừng đánh giá biểu thức khi nó gặp giá trị null đầu tiên và render view mà không có lỗi.

208. ### Có cần cấu hình đặc biệt nào cho Angular9 không?

     Bạn không cần bất kỳ cấu hình đặc biệt nào. Trong Angular9, Ivy renderer là trình biên dịch Angular mặc định. Mặc dù Ivy đã có sẵn từ Angular8, bạn đã phải cấu hình nó trong file tsconfig.json như sau,

     ```typescript
     "angularCompilerOptions": {    "enableIvy": true  }
     ```

209. ### Những thay đổi API TestBed an toàn về kiểu trong Angular9 là gì?

     Angular 9 cung cấp những thay đổi an toàn về kiểu trong API TestBed bằng cách thay thế hàm get cũ bằng phương thức inject mới. Bởi vì phương thức TestBed.get không an toàn về kiểu. Cách sử dụng sẽ như sau,

     ```typescript
     TestBed.get(ChangeDetectorRef); // trả về any. Nó đã bị deprecated.

     TestBed.inject(ChangeDetectorRef); // trả về ChangeDetectorRef
     ```

210. ### Có bắt buộc phải truyền cờ static cho ViewChild không?

     Trong Angular 8, cờ static là bắt buộc cho ViewChild. Trong khi đó ở Angular9, bạn không còn cần phải truyền thuộc tính này nữa. Một khi bạn cập nhật lên Angular9 bằng `ng update`, việc migration sẽ xóa { static: false } script ở mọi nơi.

     ```typescript
     @ViewChild(ChildDirective) child: ChildDirective; // Cách dùng trong Angular9
     @ViewChild(ChildDirective, { static: false }) child: ChildDirective; //Cách dùng trong Angular8
     ```

211. ### Danh sách các toán tử biểu thức template là gì?

     Ngôn ngữ biểu thức template Angular hỗ trợ ba toán tử biểu thức template đặc biệt.

     1. Toán tử Pipe
     2. Toán tử safe navigation
     3. Toán tử non-null assertion

212. ### Độ ưu tiên giữa toán tử pipe và ternary là gì?

     Toán tử pipe có độ ưu tiên cao hơn toán tử ternary (?:). Ví dụ, biểu thức `first ? second : third | fourth` được phân tích cú pháp thành `first ? second : (third | fourth)`.

213. ### Entry component là gì?

     Entry component là bất kỳ component nào mà Angular tải một cách bắt buộc (i.e, không tham chiếu đến nó trong template) bằng kiểu. Do hành vi này, chúng không thể được tìm thấy bởi trình biên dịch Angular trong quá trình biên dịch. Các component này được tạo động với `ComponentFactoryResolver`.

     Về cơ bản, có hai loại entry component chính là:

     1. Component root được bootstrap
     2. Component bạn chỉ định trong một route

214. ### Component được bootstrap là gì?

     Component được bootstrap là một entry component mà Angular tải vào DOM trong quá trình bootstrap hoặc thời điểm khởi chạy ứng dụng. Thông thường, component được bootstrap hay root này được đặt tên là `AppComponent` trong root module của bạn sử dụng thuộc tính `bootstrap` như dưới đây.

     ```typescript
     @NgModule({
       declarations: [
         AppComponent
       ],
       imports: [
         BrowserModule,
         FormsModule,
         HttpClientModule,
         AppRoutingModule
       ],
       providers: [],
       bootstrap: [AppComponent] // entry component được bootstrap cần được khai báo ở đây
     })
     ```

215. ### Làm thế nào để bootstrap một ứng dụng theo cách thủ công?

     Bạn có thể sử dụng hook `ngDoBootstrap` để bootstrap ứng dụng theo cách thủ công thay vì sử dụng mảng bootstrap trong annotation `@NgModule`. Hook này là một phần của interface `DoBootstrap`.

     ```typescript
     interface DoBootstrap {
       ngDoBootstrap(appRef: ApplicationRef): void;
     }
     ```

     Module cần phải triển khai interface trên để sử dụng hook cho việc bootstrapping.

     ```typescript
     class AppModule implements DoBootstrap {
       ngDoBootstrap(appRef: ApplicationRef) {
         appRef.bootstrap(AppComponent); // entry component được bootstrap cần được truyền vào
       }
     }
     ```

216. ### Có cần thiết cho component được bootstrap phải là entry component không?

     Có, component được bootstrap cần phải là một entry component. Điều này là bởi vì quá trình bootstrapping là một quá trình bắt buộc.

217. ### Routed entry component là gì?

     Các components được tham chiếu trong cấu hình router được gọi là routed entry component. Component routed entry này được định nghĩa trong định nghĩa route như dưới đây,

     ```typescript
     const routes: Routes = [
       {
         path: "",
         component: TodoListComponent, // router entry component
       },
     ];
     ```

     Vì định nghĩa router yêu cầu bạn thêm component ở hai nơi (router và entryComponents), nên các component này luôn là entry components.

     **Lưu ý:** Các trình biên dịch đủ thông minh để nhận ra định nghĩa router và tự động thêm component router vào `entryComponents`.

218. ### Tại sao không cần thiết sử dụng mảng entryComponents mọi lúc?

     Hầu hết thời gian, bạn không cần phải thiết lập rõ ràng các entry components trong mảng entryComponents của decorator ngModule. Bởi vì angular tự động thêm components từ cả @NgModule.bootstrap và định nghĩa routes vào entry components.

219. ### Tôi có cần sử dụng mảng entryComponents trong Angular9 không?

     Không. Trong các phiên bản angular trước, mảng entryComponents của decorator ngModule được sử dụng để cho trình biên dịch biết components nào sẽ được tạo và chèn động vào view. Trong Angular9, điều này không còn cần thiết nữa với Ivy.

220. ### Có phải tất cả components được tạo trong build sản phẩm?

     Không, chỉ các entry components và template components xuất hiện trong builds sản phẩm. Nếu một component không phải là entry component và không được tìm thấy trong template, tree shaker sẽ loại bỏ nó. Vì lý do này, hãy đảm bảo chỉ thêm các entry components thực sự để giảm kích thước bundle.

221. ### Angular compiler là gì?

     Angular compiler được sử dụng để chuyển đổi code ứng dụng thành code JavaScript. Nó đọc markup template, kết hợp nó với code class component tương ứng, và sinh ra các component factories sẽ tạo ra biểu diễn JavaScript của component cùng với các phần tử của metadata @Component.

222. ### Vai trò của metadata ngModule trong quá trình biên dịch là gì?

     Metadata `@NgModule` được sử dụng để nói cho Angular compiler biết những components nào cần được biên dịch cho module này và cách liên kết module này với các module khác.

223. ### Angular tìm components, directives và pipes như thế nào?

     Angular compiler tìm một component hoặc directive trong một template khi nó có thể khớp selector của component hoặc directive đó trong template đó. Trong khi đó nó tìm một pipe nếu tên của pipe xuất hiện trong cú pháp pipe của template HTML.

224. ### Cho một vài ví dụ về NgModules?

     Các thư viện core Angular và thư viện bên thứ ba có sẵn dưới dạng NgModules.

     1. Các thư viện Angular như FormsModule, HttpClientModule, và RouterModule là các NgModules.
     2. Nhiều thư viện bên thứ ba như Material Design, Ionic, và AngularFire2 là các NgModules.

225. ### Feature modules là gì?

     Feature modules là các NgModules, được sử dụng với mục đích tổ chức code. Feature module có thể được tạo với Angular CLI sử dụng lệnh dưới đây trong thư mục gốc,

     ```typescript
     ng generate module MyCustomFeature //
     ```

     Angular CLI tạo một thư mục có tên `my-custom-feature` với một file bên trong có tên `my-custom-feature.module.ts` với nội dung sau

     ```typescript
     import { NgModule } from "@angular/core";
     import { CommonModule } from "@angular/common";

     @NgModule({
       imports: [CommonModule],
       declarations: [],
     })
     export class MyCustomFeature {}
     ```

     **Lưu ý:** Hậu tố "Module" không nên có trong tên vì CLI sẽ tự động thêm nó.

226. ### Các modules được import trong feature modules được tạo bằng CLI là gì?

     Trong feature module được tạo bởi CLI, có hai câu lệnh import JavaScript ở đầu file

     1. **NgModule:** Để sử dụng decorator `@NgModule`
     2. **CommonModule:** Nó cung cấp nhiều directive phổ biến như `ngIf` và `ngFor`.

227. ### Sự khác biệt giữa ngmodule và javascript module là gì?

     Dưới đây là những khác biệt chính giữa Angular NgModule và javascript module,

     | NgModule                                                                         | JavaScript module                                            |
     | -------------------------------------------------------------------------------- | ------------------------------------------------------------ |
     | NgModule chỉ ràng buộc các class có thể khai báo                                 | Không có hạn chế về classes                                  |
     | Chỉ liệt kê các class của module trong mảng declarations                         | Có thể định nghĩa tất cả class thành viên trong một file lớn |
     | Chỉ export các class có thể khai báo mà nó sở hữu hoặc import từ các module khác | Có thể export bất kỳ class nào                               |
     | Mở rộng toàn bộ ứng dụng với services bằng cách thêm providers vào mảng provides | Không thể mở rộng ứng dụng với services                      |

228. ### Các lỗi có thể có với declarations là gì?

     Có hai lỗi phổ biến có thể có với mảng declarations,

     1. Nếu bạn sử dụng một component mà không khai báo nó, Angular sẽ trả về một thông báo lỗi.
     2. Nếu bạn cố gắng khai báo cùng một class trong nhiều module thì compiler sẽ báo lỗi.

229. ### Các bước để sử dụng các phần tử khai báo là gì?

     Dưới đây là các bước cần thực hiện để sử dụng các phần tử khai báo.

     1. Tạo phần tử (component, directive và pipes) và export nó từ file nơi bạn viết nó
     2. Import nó vào module thích hợp.
     3. Khai báo nó trong mảng declarations của @NgModule.

230. ### Điều gì xảy ra nếu browserModule được sử dụng trong feature module?

     Nếu bạn import `BrowserModule` vào một feature module được tải lazy, Angular sẽ trả về một lỗi yêu cầu bạn sử dụng `CommonModule` thay thế. Bởi vì các providers của BrowserModule là cho toàn bộ ứng dụng nên nó chỉ nên ở trong root module, không nên ở trong feature module. Trong khi đó Feature modules chỉ cần các directive phổ biến trong CommonModule.

     ![ScreenShot](images/browser-module-error.gif)

231. ### Các loại feature modules là gì?

     Dưới đây là năm loại feature modules,

     1. **Domain:** Cung cấp trải nghiệm người dùng dành riêng cho một miền ứng dụng cụ thể (Ví dụ, đặt hàng, đăng ký v.v.)
     2. **Routed:** Đây là các domain feature module mà các components đầu của chúng là mục tiêu của các route điều hướng router.
     3. **Routing:** Nó cung cấp cấu hình routing cho một module khác.
     4. **Service:** Nó cung cấp các service tiện ích như truy cập dữ liệu và messaging (Ví dụ, HttpClientModule)
     5. **Widget:** Nó làm cho các components, directives và pipes có sẵn cho các module bên ngoài (Ví dụ, các thư viện bên thứ ba như Material UI)

232. ### Provider là gì?

     Provider là một hướng dẫn cho hệ thống Dependency Injection về cách lấy giá trị cho một dependency (hay còn gọi là services đã tạo). Service có thể được cung cấp bằng Angular CLI như sau,

     ```typescript
     ng generate service my-service
     ```

     Service được tạo bởi CLI sẽ như sau,

     ```typescript
     import { Injectable } from "@angular/core";

     @Injectable({
       providedIn: "root", //Angular cung cấp service trong root injector
     })
     export class MyService {}
     ```

233. ### Khuyến nghị cho phạm vi provider là gì?

     Bạn nên luôn cung cấp service của bạn trong root injector trừ khi có trường hợp bạn muốn service chỉ có sẵn nếu bạn import một @NgModule cụ thể.

234. ### Làm thế nào để hạn chế phạm vi provider đến một module?

     Có thể hạn chế phạm vi provider service đến một module cụ thể thay vì làm cho nó có sẵn cho toàn bộ ứng dụng. Có hai cách có thể làm điều này.

     1. **Sử dụng providedIn trong service:**

        ```typescript
        import { Injectable } from "@angular/core";
        import { SomeModule } from "./some.module";

        @Injectable({
          providedIn: SomeModule,
        })
        export class SomeService {}
        ```

     2. **Khai báo provider cho service trong module:**

        ```typescript
        import { NgModule } from "@angular/core";

        import { SomeService } from "./some.service";

        @NgModule({
          providers: [SomeService],
        })
        export class SomeModule {}
        ```

235. ### Làm thế nào để cung cấp một service singleton?

     Có hai cách có thể để cung cấp một service singleton.

     1. Đặt thuộc tính providedIn của @Injectable() thành "root". Đây là cách được ưa thích (bắt đầu từ Angular 6.0) để tạo một service singleton vì nó làm cho services của bạn có thể tree-shakable.

        ```typescript
        import { Injectable } from "@angular/core";

        @Injectable({
          providedIn: "root",
        })
        export class MyService {}
        ```

     2. Include service trong root module hoặc trong một module chỉ được import bởi root module. Nó đã được sử dụng để đăng ký services trước Angular 6.0.

        ```typescript
        @NgModule({
          ...
          providers: [MyService],
          ...
        })
        ```

236. ### Các cách khác nhau để loại bỏ việc đăng ký service trùng lặp là gì?

     Nếu một module định nghĩa providers và declarations thì việc tải module đó trong nhiều feature modules sẽ làm trùng lặp việc đăng ký service. Dưới đây là các cách khác nhau để ngăn chặn hành vi trùng lặp này.

     1. Sử dụng cú pháp providedIn thay vì đăng ký service trong module.
     2. Tách các services của bạn thành module riêng của chúng.
     3. Định nghĩa các phương thức forRoot() và forChild() trong module.

237. ### Phương thức forRoot giúp tránh các instance router trùng lặp như thế nào?

     Nếu module `RouterModule` không có phương thức static forRoot() thì mỗi feature module sẽ khởi tạo một instance Router mới, điều này dẫn đến ứng dụng bị hỏng do các instance trùng lặp. Sau khi sử dụng phương thức forRoot(), module ứng dụng gốc imports `RouterModule.forRoot(...)` và nhận một Router, và tất cả các feature modules imports `RouterModule.forChild(...)` không khởi tạo Router khác.

238. ### Shared module là gì?

     Shared Module là module trong đó bạn đặt các directives, pipes và components thường được sử dụng vào một module được chia sẻ (import) trong toàn bộ ứng dụng.

     Ví dụ, shared module dưới đây imports CommonModule, FormsModule cho các directives phổ biến và components, pipes và directives dựa trên nhu cầu,

     ```typescript
     import { CommonModule } from "@angular/common";
     import { NgModule } from "@angular/core";
     import { FormsModule } from "@angular/forms";
     import { UserComponent } from "./user.component";
     import { NewUserDirective } from "./new-user.directive";
     import { OrdersPipe } from "./orders.pipe";

     @NgModule({
       imports: [CommonModule],
       declarations: [UserComponent, NewUserDirective, OrdersPipe],
       exports: [
         UserComponent,
         NewUserDirective,
         OrdersPipe,
         CommonModule,
         FormsModule,
       ],
     })
     export class SharedModule {}
     ```

239. ### Tôi có thể chia sẻ services bằng modules không?

     Không, không được khuyến nghị chia sẻ services bằng cách import module. i.e Import modules khi bạn muốn sử dụng directives, pipes và components. Cách tiếp cận tốt nhất để nắm bắt các shared services là thông qua 'Angular dependency injection' bởi vì việc import một module sẽ tạo ra một instance service mới.

240. ### Làm thế nào để lấy hướng hiện tại cho locales?

     Trong Angular 9.1, phương thức API `getLocaleDirection` có thể được sử dụng để lấy hướng hiện tại trong ứng dụng của bạn. Phương thức này hữu ích để hỗ trợ các locales Phải sang Trái cho các ứng dụng Internationalization của bạn.

     ```typescript
     import { getLocaleDirection, registerLocaleData } from '@angular/common';
     import { LOCALE_ID } from '@angular/core';
     import localeAr from '@angular/common/locales/ar';

       ...

       constructor(@Inject(LOCALE_ID) locale) {

         const directionForLocale = getLocaleDirection(locale); // Trả về 'rtl' hoặc 'ltr' dựa trên locale hiện tại
         registerLocaleData(localeAr, 'ar-ae');
         const direction = getLocaleDirection('ar-ae'); // Trả về 'rtl'

         // Hướng hiện tại được sử dụng để cung cấp logic điều kiện ở đây
       }
     ```

241. ### Ngcc là gì?

     Ngcc (Angular Compatibility Compiler) là một công cụ nâng cấp node_module được biên dịch với ngc không phải ivy thành định dạng tương thích với ivy. Script `postinstall` từ package.json sẽ đảm bảo node_modules của bạn sẽ tương thích với trình render Ivy.

     ```typescript
     "scripts": {
        "postinstall": "ngcc"
     }
     ```

     Trong khi đó, Ivy compiler (ngtsc), biên dịch code tương thích với Ivy.

242. ### Những class nào không nên được thêm vào declarations?

     Các loại class dưới đây không nên được thêm vào declarations

     1. Class đã được khai báo trong bất kỳ module nào khác.
     2. Directives được import từ module khác.
     3. Class Module.
     4. Class Service.
     5. Các class và object không phải Angular, như strings, numbers, functions, entity models, configurations, business logic và helper classes.

243. ### NgZone là gì?

     Angular cung cấp một service gọi là NgZone tạo ra một zone có tên `angular` để tự động kích hoạt phát hiện thay đổi khi các điều kiện sau được thỏa mãn.

     1. Khi một hàm sync hoặc async được thực thi.
     2. Khi không có microTask nào được lên lịch.

244. ### NoopZone là gì?

     Zone được tải/yêu cầu theo mặc định trong các ứng dụng Angular và nó giúp Angular biết khi nào kích hoạt phát hiện thay đổi. Bằng cách này, nó đảm bảo các nhà phát triển tập trung vào phát triển ứng dụng hơn là phần core của Angular. Bạn cũng có thể sử dụng Angular mà không có Zone nhưng phát hiện thay đổi cần được triển khai trên chính bạn và `noop zone` cần được cấu hình trong quá trình bootstrap.
     Hãy làm theo hai bước dưới đây để loại bỏ zone.js,

     1. Loại bỏ import zone.js khỏi polyfills.ts.
        ```typescript
        /***************************************************************************************************
         * Zone JS is required by default for Angular itself.
         */
        // import 'zone.js/dist/zone';  // Included with Angular CLI.
        ```
     2. Bootstrap Angular với noop zone trong src/main.ts.
        ```typescript
        platformBrowserDynamic()
          .bootstrapModule(AppModule, { ngZone: "noop" })
          .catch((err) => console.error(err));
        ```

245. ### Làm thế nào để tạo components displayBlock?

     Theo mặc định, Angular CLI tạo các components ở chế độ hiển thị inline (i.e, display:inline). Nhưng có thể tạo components với style display: block bằng tùy chọn `displayBlock`,

     ```typescript
     ng generate component my-component --displayBlock
     ```

     (HOẶC) tùy chọn có thể được bật mặc định trong Angular.json với khóa `schematics.@schematics/angular:component.displayBlock` có giá trị true.

246. ### Các kịch bản cập nhật dữ liệu có thể có cho phát hiện thay đổi là gì?

     Phát hiện thay đổi hoạt động trong các kịch bản sau đây khi các thay đổi dữ liệu cần cập nhật HTML của ứng dụng.

     1. **Khởi tạo Component:** Trong khi bootstrap ứng dụng Angular, Angular kích hoạt `ApplicationRef.tick()` để gọi phát hiện thay đổi và View Rendering.
     2. **Event listener:** DOM event listener có thể cập nhật dữ liệu trong một Angular component và kích hoạt phát hiện thay đổi.

        ```typescript
        @Component({
          selector: "app-event-listener",
          template: ` <button (click)="onClick()">Click</button>
            {{ message }}`,
        })
        export class EventListenerComponent {
          message = "";

          onClick() {
            this.message = "data updated";
          }
        }
        ```

     3. **HTTP Data Request:** Bạn có thể lấy dữ liệu từ server thông qua một HTTP request

        ```typescript
        data = 'default value';
        constructor(private httpClient: HttpClient) {}

          ngOnInit() {
            this.httpClient.get(this.serverUrl).subscribe(response => {
              this.data = response.data; // phát hiện thay đổi sẽ xảy ra tự động
            });
          }
        ```

     4. **Macro tasks setTimeout() hoặc setInterval():** Bạn có thể cập nhật dữ liệu trong hàm callback của setTimeout hoặc setInterval

        ```typescript
        data = 'default value';

          ngOnInit() {
            setTimeout(() => {
              this.data = 'data updated'; // Phát hiện thay đổi sẽ xảy ra tự động
            });
          }
        ```

     5. **Micro tasks Promises:** Bạn có thể cập nhật dữ liệu trong hàm callback của promise

        ```typescript
        data = 'initial value';

          ngOnInit() {
            Promise.resolve(1).then(v => {
              this.data = v; // Phát hiện thay đổi sẽ xảy ra tự động
            });
          }
        ```

     6. **Async operations như Web sockets và Canvas:** Dữ liệu có thể được cập nhật bất đồng bộ sử dụng WebSocket.onmessage() và Canvas.toBlob().

247. ### Zone context là gì?

     Execution Context là một khái niệm trừu tượng chứa thông tin về môi trường trong code hiện tại đang được thực thi. Zone cung cấp một execution context tồn tại qua các hoạt động bất đồng bộ được gọi là zone context. Ví dụ, zone context sẽ giống nhau ở cả bên ngoài và bên trong hàm callback setTimeout,

     ```typescript
     zone.run(() => {
       // outside zone
       expect(zoneThis).toBe(zone);
       setTimeout(function () {
         // the same outside zone exist here
         expect(zoneThis).toBe(zone);
       });
     });
     ```

     Zone hiện tại được lấy thông qua `Zone.current`.

248. ### Các lifecycle hooks của zone là gì?

     Có bốn lifecycle hooks cho các hoạt động bất đồng bộ từ zone.js.

     1. **onScheduleTask:** Hook này kích hoạt khi một task bất đồng bộ mới được lên lịch. Ví dụ, khi bạn gọi setTimeout()
        ```typescript
        onScheduleTask: function(delegate, curr, target, task) {
            console.log('new task is scheduled:', task.type, task.source);
            return delegate.scheduleTask(target, task);
          }
        ```
     2. **onInvokeTask:** Hook này kích hoạt khi một task bất đồng bộ sắp thực thi. Ví dụ, khi callback của setTimeout() sắp được thực thi.
        ```typescript
        onInvokeTask: function(delegate, curr, target, task, applyThis, applyArgs) {
            console.log('task will be invoked:', task.type, task.source);
            return delegate.invokeTask(target, task, applyThis, applyArgs);
          }
        ```
     3. **onHasTask:** Hook này kích hoạt khi trạng thái của một loại task bên trong zone thay đổi từ ổn định (không có task nào trong zone) sang không ổn định (một task mới được lên lịch trong zone) hoặc từ không ổn định sang ổn định.
        ```typescript
          onHasTask: function(delegate, curr, target, hasTaskState) {
            console.log('task state changed in the zone:', hasTaskState);
            return delegate.hasTask(target, hasTaskState);
          }
        ```
     4. **onInvoke:** Hook này kích hoạt khi một hàm đồng bộ sắp được thực thi trong zone.
        ```typescript
        onInvoke: function(delegate, curr, target, callback, applyThis, applyArgs) {
            console.log('the callback will be invoked:', callback);
            return delegate.invoke(target, callback, applyThis, applyArgs);
          }
        ```

249. ### Các phương thức của NgZone được sử dụng để kiểm soát phát hiện thay đổi là gì?

     Service NgZone cung cấp một phương thức `run()` cho phép bạn thực thi một hàm bên trong angular zone. Hàm này được sử dụng để thực thi các API bên thứ ba không được xử lý bởi Zone và kích hoạt phát hiện thay đổi tự động tại thời điểm thích hợp.

     ```typescript
     export class AppComponent implements OnInit {
       constructor(private ngZone: NgZone) {}
       ngOnInit() {
         // sử dụng ngZone.run() để thực hiện hoạt động bất đồng bộ trong angular zone
         this.ngZone.run(() => {
           someNewAsyncAPI(() => {
             // cập nhật dữ liệu của component
           });
         });
       }
     }
     ```

     Trong khi đó phương thức `runOutsideAngular()` được sử dụng khi bạn không muốn kích hoạt phát hiện thay đổi.

     ```typescript
     export class AppComponent implements OnInit {
       constructor(private ngZone: NgZone) {}
       ngOnInit() {
         // Sử dụng phương thức này khi bạn biết không có dữ liệu nào sẽ được cập nhật
         this.ngZone.runOutsideAngular(() => {
           setTimeout(() => {
             // cập nhật dữ liệu component và không kích hoạt phát hiện thay đổi
           });
         });
       }
     }
     ```

250. ### Làm thế nào để thay đổi cài đặt của zonejs?

     Bạn có thể thay đổi cài đặt của zone bằng cách cấu hình chúng trong một file riêng và import nó ngay sau import zonejs.
     Ví dụ, bạn có thể tắt monkey patch requestAnimationFrame() để ngăn phát hiện thay đổi khi không có cập nhật dữ liệu như một cài đặt và ngăn các sự kiện DOM (sự kiện mousemove hoặc scroll) kích hoạt phát hiện thay đổi. Giả sử file mới có tên zone-flags.js,

     ```typescript
     // disable patching requestAnimationFrame
     (window as any).__Zone_disable_requestAnimationFrame = true;

     // disable patching specified eventNames
     (window as any).__zone_symbol__UNPATCHED_EVENTS = ["scroll", "mousemove"];
     ```

     File cấu hình trên có thể được import trong file polyfill.ts như dưới đây,

     ```typescript
     /***************************************************************************************************
      * Zone JS is required by default for Angular.
      */
     import `./zone-flags`;
     import 'zone.js/dist/zone';  // Included with Angular CLI.
     ```



     251. ### Làm thế nào để kích hoạt một animation?

     Angular cung cấp hàm `trigger()` cho animation để thu thập các trạng thái và transitions với một tên animation cụ thể, để bạn có thể gắn nó vào phần tử kích hoạt trong template HTML. Hàm này theo dõi các thay đổi và kích hoạt các hành động khi có thay đổi xảy ra.
     Ví dụ, hãy tạo một trigger có tên `upDown`, và gắn nó vào phần tử button.

     ```typescript
     @Component({
       selector: "app-up-down",
       animations: [
         trigger("upDown", [
           state(
             "up",
             style({
               height: "200px",
               opacity: 1,
               backgroundColor: "yellow",
             })
           ),
           state(
             "down",
             style({
               height: "100px",
               opacity: 0.5,
               backgroundColor: "green",
             })
           ),
           transition("up => down", [animate("1s")]),
           transition("down => up", [animate("0.5s")]),
         ]),
       ],
       templateUrl: "up-down.component.html",
       styleUrls: ["up-down.component.css"],
     })
     export class UpDownComponent {
       isUp = true;

       toggle() {
         this.isUp = !this.isUp;
       }
     }
     ```

252. ### Làm thế nào để cấu hình injectors với providers ở các cấp độ khác nhau?

     Bạn có thể cấu hình injectors với providers ở các cấp độ khác nhau trong ứng dụng của bạn bằng cách thiết lập giá trị metadata. Việc cấu hình có thể xảy ra ở một trong ba nơi,

     1. Trong decorator `@Injectable()` cho chính service
     2. Trong decorator `@NgModule()` cho một NgModule
     3. Trong decorator `@Component()` cho một component

253. ### Có bắt buộc phải sử dụng injectable trên mọi class service không?

     Không. Decorator `@Injectable()` không thực sự bắt buộc nếu class có các decorators Angular khác trên nó hoặc không có bất kỳ dependencies nào. Nhưng điều quan trọng ở đây là bất kỳ class nào sẽ được inject với Angular đều được trang trí.
     i.e, Nếu chúng ta thêm decorator, metadata `design:paramtypes` được thêm vào, và dependency injection có thể làm công việc của nó. Đó là lý do chính xác để thêm decorator @Injectable() vào một service nếu service này có một số dependencies.
     Ví dụ, hãy xem các biến thể khác nhau của AppService trong root component,

     1. AppService dưới đây có thể được inject trong AppComponent mà không có vấn đề gì. Điều này là do không có service dependencies nào bên trong AppService.
        ```typescript
        export class AppService {
          constructor() {
            console.log("A new app service");
          }
        }
        ```
     2. AppService dưới đây với decorator giả và httpService có thể được inject trong AppComponent mà không có vấn đề gì. Điều này là do thông tin meta được tạo ra với decorator giả.

        ```typescript
        function SomeDummyDecorator() {
          return (constructor: Function) => console.log(constructor);
        }

        @SomeDummyDecorator()
        export class AppService {
          constructor(http: HttpService) {
            console.log(http);
          }
        }
        ```

        và code javascript được tạo ra của service trên có thông tin meta về HttpService,

        ```typescript
        var AppService = (function () {
          function AppService(http) {
            console.log(http);
          }
          AppService = __decorate(
            [
              core_1.Injectable(),
              __metadata("design:paramtypes", [http_service_1.HttpService]),
            ],
            AppService
          );
          return AppService;
        })();
        exports.AppService = AppService;
        ```

     3. AppService dưới đây với decorator @injectable và httpService có thể được inject trong AppComponent mà không có vấn đề gì. Điều này là do thông tin meta được tạo ra với decorator Injectable.
        ```typescript
        @Injectable({
          providedIn: "root",
        })
        export class AppService {
          constructor(http: HttpService) {
            console.log(http);
          }
        }
        ```

254. ### Optional dependency là gì?

     Optional dependency là một decorator tham số được sử dụng trên các tham số constructor, nó đánh dấu tham số là một dependency tùy chọn. Do điều này, framework DI cung cấp null nếu dependency không được tìm thấy.
     Ví dụ, Nếu bạn không đăng ký provider logger ở bất kỳ đâu, injector đặt giá trị của logger (hoặc logger service) thành null trong class dưới đây.

     ```typescript
     import { Optional } from '@angular/core';

     constructor(@Optional() private logger?: Logger) {
       if (this.logger) {
         this.logger.log('This is an optional dependency message');
       } else {
         console.log('The logger is not registered');
       }
     }
     ```

255. ### Các loại injector hierarchies là gì?

     Có hai loại injector hierarchies trong Angular

     1. **ModuleInjector hierarchy:** Nó được cấu hình ở cấp độ module bằng cách sử dụng annotation @NgModule() hoặc @Injectable().
     2. **ElementInjector hierarchy:** Nó được tạo ra ngầm định tại mỗi phần tử DOM. Ngoài ra nó trống theo mặc định trừ khi bạn cấu hình nó trong thuộc tính providers trên @Directive() hoặc @Component().

256. ### Reactive forms là gì?

     Reactive forms là một cách tiếp cận model-driven để tạo forms theo kiểu reactive (các inputs form thay đổi theo thời gian). Chúng được xây dựng xung quanh các observable streams, trong đó các form inputs và values được cung cấp dưới dạng các streams giá trị input. Hãy làm theo các bước dưới đây để tạo reactive forms,

     1. Đăng ký reactive forms module khai báo các reactive-form directives trong app của bạn

        ```typescript
        import { ReactiveFormsModule } from "@angular/forms";

        @NgModule({
          imports: [
            // other imports ...
            ReactiveFormsModule,
          ],
        })
        export class AppModule {}
        ```

     2. Tạo một instance FormControl mới và lưu nó trong component.

        ```typescript
        import { Component } from "@angular/core";
        import { FormControl } from "@angular/forms";

        @Component({
          selector: "user-profile",
          styleUrls: ["./user-profile.component.css"],
        })
        export class UserProfileComponent {
          userName = new FormControl("");
        }
        ```

     3. Đăng ký FormControl trong template.

        ```html
        <label>
          User name:
          <input type="text" [formControl]="userName" />
        </label>
        ```

        Cuối cùng, component với reactive form control sẽ xuất hiện như sau,

        ```typescript
        import { Component } from "@angular/core";
        import { FormControl } from "@angular/forms";

        @Component({
          selector: "user-profile",
          styleUrls: ["./user-profile.component.css"],
          template: `
            <label>
              User name:
              <input type="text" [formControl]="userName" />
            </label>
          `,
        })
        export class UserProfileComponent {
          userName = new FormControl("");
        }
        ```

257. ### Dynamic forms là gì?

     Dynamic forms là một pattern trong đó chúng ta xây dựng một form động dựa trên metadata mô tả một business object model. Bạn có thể tạo chúng dựa trên reactive form API.

258. ### Template driven forms là gì?

     Template driven forms là các forms model-driven trong đó bạn viết logic, validations, controls v.v., trong phần template của code bằng cách sử dụng các directives. Chúng phù hợp cho các kịch bản đơn giản và sử dụng two-way binding với cú pháp [(ngModel)].
     Ví dụ, bạn có thể tạo form đăng ký dễ dàng bằng cách làm theo các bước đơn giản dưới đây,

     1. Import FormsModule vào mảng imports của Application module
        ```typescript
        import { BrowserModule } from "@angular/platform-browser";
        import { NgModule } from "@angular/core";
        import { FormsModule } from "@angular/forms";
        import { RegisterComponent } from "./app.component";
        @NgModule({
          declarations: [RegisterComponent],
          imports: [BrowserModule, FormsModule],
          providers: [],
          bootstrap: [RegisterComponent],
        })
        export class AppModule {}
        ```
     2. Bind form từ template đến component sử dụng cú pháp ngModel
        ```html
        <input
          type="text"
          class="form-control"
          id="name"
          required
          [(ngModel)]="model.name"
          name="name"
        />
        ```
     3. Đính kèm directive NgForm vào thẻ <form> để tạo các instances FormControl và đăng ký chúng
        ```typescript
        <form #registerForm="ngForm">
        ```
     4. Áp dụng thông báo validation cho form controls
        ```html
        <label for="name">Name</label>
        <input
          type="text"
          class="form-control"
          id="name"
          required
          [(ngModel)]="model.name"
          name="name"
          #name="ngModel"
        />
        <div [hidden]="name.valid || name.pristine" class="alert alert-danger">
          Please enter your name
        </div>
        ```
     5. Submit form với directive ngSubmit và thêm button type="submit" ở cuối form để kích hoạt form submit.

        ```html
        <form (ngSubmit)="onSubmit()" #heroForm="ngForm">
          // Form goes here
          <button
            type="submit"
            class="btn btn-success"
            [disabled]="!registerForm.form.valid"
          >
            Submit
          </button>
        </form>
        ```

        Cuối cùng, form đăng ký template-driven hoàn chỉnh sẽ xuất hiện như sau.

        ```html
        <div class="container">
          <h1>Registration Form</h1>
          <form (ngSubmit)="onSubmit()" #registerForm="ngForm">
            <div class="form-group">
              <label for="name">Name</label>
              <input
                type="text"
                class="form-control"
                id="name"
                required
                [(ngModel)]="model.name"
                name="name"
                #name="ngModel"
              />
              <div
                [hidden]="name.valid || name.pristine"
                class="alert alert-danger"
              >
                Please enter your name
              </div>
            </div>
            <button
              type="submit"
              class="btn btn-success"
              [disabled]="!registerForm.form.valid"
            >
              Submit
            </button>
          </form>
        </div>
        ```

259. ### Sự khác biệt giữa reactive forms và template driven forms là gì?

     Dưới đây là những khác biệt chính giữa reactive forms và template driven forms

     | Tính năng              | Reactive                                                          | Template-Driven                                     |
     | ---------------------- | ----------------------------------------------------------------- | --------------------------------------------------- |
     | Thiết lập form model   | Tạo trong component (instance FormControl)                        | Tạo bởi directives                                  |
     | Cập nhật dữ liệu       | Đồng bộ                                                           | Bất đồng bộ                                         |
     | Form custom validation | Định nghĩa như Functions                                          | Định nghĩa như Directives                           |
     | Testing                | Không tương tác với chu kỳ phát hiện thay đổi                     | Cần kiến thức về quá trình phát hiện thay đổi       |
     | Tính thay đổi          | Không thay đổi (luôn trả về giá trị mới cho instance FormControl) | Thay đổi (Property luôn được sửa thành giá trị mới) |
     | Khả năng mở rộng       | Dễ mở rộng hơn sử dụng APIs cấp thấp                              | Khó mở rộng hơn do trừu tượng hóa trên APIs         |

260. ### Những cách khác nhau để nhóm các form controls là gì?

     Reactive forms cung cấp hai cách để nhóm nhiều controls liên quan.

     1. **FormGroup**: Nó định nghĩa một form với một tập các controls cố định có thể được quản lý cùng nhau trong một đối tượng. Nó có cùng thuộc tính và phương thức giống như instance FormControl.
        FormGroup này có thể được lồng nhau để tạo forms phức tạp như dưới đây.

        ```typescript
        import { Component } from "@angular/core";
        import { FormGroup, FormControl } from "@angular/forms";

        @Component({
          selector: "user-profile",
          templateUrl: "./user-profile.component.html",
          styleUrls: ["./user-profile.component.css"],
        })
        export class UserProfileComponent {
          userProfile = new FormGroup({
            firstName: new FormControl(""),
            lastName: new FormControl(""),
            address: new FormGroup({
              street: new FormControl(""),
              city: new FormControl(""),
              state: new FormControl(""),
              zip: new FormControl(""),
            }),
          });

          onSubmit() {
            // Store this.userProfile.value in DB
          }
        }
        ```

        ```html
        <form [formGroup]="userProfile" (ngSubmit)="onSubmit()">
          <label>
            First Name:
            <input type="text" formControlName="firstName" />
          </label>

          <label>
            Last Name:
            <input type="text" formControlName="lastName" />
          </label>

          <div formGroupName="address">
            <h3>Address</h3>

            <label>
              Street:
              <input type="text" formControlName="street" />
            </label>

            <label>
              City:
              <input type="text" formControlName="city" />
            </label>

            <label>
              State:
              <input type="text" formControlName="state" />
            </label>

            <label>
              Zip Code:
              <input type="text" formControlName="zip" />
            </label>
          </div>
          <button type="submit" [disabled]="!userProfile.valid">Submit</button>
        </form>
        ```

     2. **FormArray**: Nó định nghĩa một form dưới dạng mảng, nơi bạn có thể thêm và xóa controls tại thời điểm chạy. Điều này hữu ích cho các forms động khi bạn không biết sẽ có bao nhiêu controls sẽ có mặt trong group.

        ```typescript
        import { Component } from "@angular/core";
        import { FormArray, FormControl } from "@angular/forms";

        @Component({
          selector: "order-form",
          templateUrl: "./order-form.component.html",
          styleUrls: ["./order-form.component.css"],
        })
        export class OrderFormComponent {
          constructor() {
            this.orderForm = new FormGroup({
              firstName: new FormControl("John", Validators.minLength(3)),
              lastName: new FormControl("Rodson"),
              items: new FormArray([new FormControl(null)]),
            });
          }

          onSubmitForm() {
            // Save the items this.orderForm.value in DB
          }

          onAddItem() {
            this.orderForm.controls.items.push(new FormControl(null));
          }

          onRemoveItem(index) {
            this.orderForm.controls["items"].removeAt(index);
          }
        }
        ```

        ```html
        <form [formGroup]="orderForm" (ngSubmit)="onSubmit()">
          <label>
            First Name:
            <input type="text" formControlName="firstName" />
          </label>

          <label>
            Last Name:
            <input type="text" formControlName="lastName" />
          </label>

          <div>
            <p>Add items</p>
            <ul formArrayName="items">
              <li
                *ngFor="let item of orderForm.controls.items.controls; let i = index"
              >
                <input type="text" formControlName="{{i}}" />
                <button
                  type="button"
                  title="Remove Item"
                  (click)="onRemoveItem(i)"
                >
                  Remove
                </button>
              </li>
            </ul>
            <button type="button" (click)="onAddItem">Add an item</button>
          </div>
        </form>
        ```

261. ### Làm thế nào để cập nhật các thuộc tính cụ thể của form model?

     Bạn có thể sử dụng phương thức `patchValue()` để cập nhật các thuộc tính cụ thể được định nghĩa trong form model. Ví dụ, bạn có thể cập nhật tên và đường của một profile nhất định khi click vào nút update như dưới đây.

     ```typescript
     updateProfile() {
       this.userProfile.patchValue({
         firstName: 'John',
         address: {
           street: '98 Crescent Street'
         }
       });
     }
     ```

     ```html
     <button (click)="updateProfile()">Update Profile</button>
     ```

     Bạn cũng có thể sử dụng phương thức `setValue` để cập nhật thuộc tính.

     **Lưu ý:** Nhớ cập nhật các thuộc tính theo đúng cấu trúc model.

262. ### Mục đích của FormBuilder là gì?

     FormBuilder được sử dụng như một cú pháp đơn giản hóa để dễ dàng tạo instances của một FormControl, FormGroup, hoặc FormArray. Điều này hữu ích để giảm lượng boilerplate cần thiết để xây dựng các reactive forms phức tạp. Nó có sẵn như một class helper có thể inject của package `@angular/forms`.

     Ví dụ, việc tạo component user profile trở nên dễ dàng hơn như sau.

     ```typescript
     export class UserProfileComponent {
       profileForm = this.formBuilder.group({
         firstName: [""],
         lastName: [""],
         address: this.formBuilder.group({
           street: [""],
           city: [""],
           state: [""],
           zip: [""],
         }),
       });
       constructor(private formBuilder: FormBuilder) {}
     }
     ```

263. ### Làm thế nào để xác minh các thay đổi model trong forms?

     Bạn có thể thêm một thuộc tính getter (giả sử là diagnostic) bên trong component để trả về một biểu diễn JSON của model trong quá trình phát triển. Điều này hữu ích để xác minh liệu các giá trị có thực sự chảy từ input box đến model và ngược lại hay không.

     ```typescript
     export class UserProfileComponent {
       model = new User("John", 29, "Writer");

       // TODO: Remove sau khi xác minh
       get diagnostic() {
         return JSON.stringify(this.model);
       }
     }
     ```

     và thêm binding diagnostic gần đầu form

     ```html
     {{diagnostic}}
     <div class="form-group">// FormControls goes here</div>
     ```

264. ### CSS classes được cung cấp bởi ngModel là gì?

     Directive ngModel cập nhật form control với các CSS class đặc biệt của Angular để phản ánh trạng thái của nó. Hãy tìm danh sách các classes trong bảng dưới đây,

     | Trạng thái form control | Nếu true   | Nếu false    |
     | ----------------------- | ---------- | ------------ |
     | Đã truy cập             | ng-touched | ng-untouched |
     | Giá trị đã thay đổi     | ng-dirty   | ng-pristine  |
     | Giá trị hợp lệ          | ng-valid   | ng-invalid   |

265. ### Làm thế nào để reset form?

     Trong một form model-driven, bạn có thể reset form chỉ bằng cách gọi hàm `reset()` trên form model của chúng ta.
     Ví dụ, bạn có thể reset form model khi submit như sau,

     ```typescript
     onSubmit() {
       if (this.myform.valid) {
         console.log("Form is submitted");
         // Thực hiện business logic ở đây
         this.myform.reset();
       }
     }
     ```

     Bây giờ, form model của bạn sẽ reset form trở lại trạng thái pristine ban đầu.

266. ### Các loại hàm validator là gì?

     Trong reactive forms, các validators có thể là các hàm đồng bộ hoặc bất đồng bộ,

     1. **Sync validators:** Đây là các hàm đồng bộ nhận một control instance và ngay lập tức trả về hoặc một tập các lỗi validation hoặc null. Ngoài ra, các hàm này được truyền vào như tham số thứ hai khi khởi tạo form control. Các use cases chính là kiểm tra đơn giản như liệu một trường có trống không, liệu nó có vượt quá độ dài tối đa không v.v.
     2. **Async validators:** Đây là các hàm bất đồng bộ nhận một control instance và trả về một Promise hoặc Observable sau đó phát ra một tập các lỗi validation hoặc null. Ngoài ra, các hàm này được truyền vào như tham số thứ hai khi khởi tạo form control. Các use cases chính là validation phức tạp như gọi server để kiểm tra tính khả dụng của một username hoặc email.

     Biểu diễn của các validators này trông như dưới đây

     ```typescript
     this.myForm = formBuilder.group({
         firstName: ['value'],
         lastName: ['value', *Một hàm validation đồng bộ*],
         email: ['value', *Một hàm validation*, *Một hàm validation bất đồng bộ*]
     });
     ```

267. ### Bạn có thể cho một ví dụ về built-in validators không?

     Trong reactive forms, bạn có thể sử dụng các validator built-in như `required` và `minlength` trên các form controls của input. Ví dụ, form đăng ký có thể có các validators này trên trường input name

     ```typescript
     this.registrationForm = new FormGroup({
       name: new FormControl(this.hero.name, [
         Validators.required,
         Validators.minLength(4),
       ]),
     });
     ```

     Trong khi đó trong template-driven forms, cả hai validator `required` và `minlength` đều có sẵn dưới dạng attributes.

268. ### Làm thế nào để tối ưu hóa hiệu suất của async validators?

     Vì tất cả validators chạy sau mỗi lần form value thay đổi, nó tạo ra một tác động lớn đến hiệu suất với async validators bằng cách gọi API bên ngoài trên mỗi lần gõ phím. Tình huống này có thể được tránh bằng cách trì hoãn tính hợp lệ của form bằng cách thay đổi thuộc tính updateOn từ change (mặc định) thành submit hoặc blur.
     Cách sử dụng sẽ khác nhau dựa trên loại form,

     1. **Template-driven forms:** Đặt thuộc tính trên directive `ngModelOptions`
        ```html
        <input [(ngModel)]="name" [ngModelOptions]="{updateOn: 'blur'}" />
        ```
     2. **Reactive-forms:** Đặt thuộc tính trên instance FormControl
        ```typescript
        name = new FormControl("", { updateOn: "blur" });
        ```

269. ### Làm thế nào để đặt ngFor và ngIf trên cùng một phần tử?

     Đôi khi bạn có thể cần cả ngFor và ngIf trên cùng một phần tử nhưng không may bạn sẽ gặp lỗi template dưới đây.

     ```cmd
     Template parse errors: Can't have multiple template bindings on one element.
     ```

     Trong trường hợp này, bạn cần sử dụng ng-container hoặc ng-template.
     Giả sử nếu bạn cố gắng lặp qua các items chỉ khi có items, đoạn code dưới đây sẽ throw một lỗi trong trình duyệt

     ```html
     <ul *ngIf="items" *ngFor="let item of items">
       <li></li>
     </ul>
     ```

     và nó có thể được sửa bằng

     ```html
     <ng-container *ngIf="items">
       <ul *ngFor="let item of items">
         <li></li>
       </ul>
     </ng-container>
     ```

270. ### Host property trong css là gì?

     Bộ chọn pseudo-class `:host` được sử dụng để nhắm mục tiêu styles trong phần tử host chứa component. Vì phần tử host nằm trong template của component cha, bạn không thể tiếp cận phần tử host từ bên trong component bằng các cách khác.
     Ví dụ, bạn có thể tạo một border cho phần tử cha như dưới đây,

     ```css
     //Other styles for app.component.css
     //...
     :host {
       display: block;
       border: 1px solid black;
       padding: 20px;
     }
     ```

271. ### Làm thế nào để lấy route hiện tại?

     Trong Angular, có một thuộc tính `url` của package router để lấy route hiện tại. Bạn cần làm theo các bước sau,

     1. Import Router từ @angular/router

        ```typescript
        import { Router } from "@angular/router";
        ```

     2. Inject router trong constructor

        ```typescript
        constructor(private router: Router ) {

        }
        ```

     3. Truy cập tham số url

        ```typescript
        console.log(this.router.url); //  /routename
        ```

272. ### Component Test Harnesses là gì?

     Component harness là một API testing xung quanh một directive hoặc component của Angular để làm cho tests đơn giản hơn bằng cách ẩn các chi tiết triển khai khỏi test suites. Điều này có thể được chia sẻ giữa các unit tests, integration tests, và end-to-end tests. Ý tưởng cho component harnesses đến từ pattern **PageObject** thường được sử dụng cho integration testing.

273. ### Lợi ích của Automatic Inlining of Fonts là gì?

     Trong thời gian biên dịch, Angular CLI sẽ tải xuống và inline các fonts mà ứng dụng của bạn đang sử dụng. Cập nhật hiệu suất này tăng tốc first contentful paint (FCP) và tính năng này được bật mặc định trong các ứng dụng được build với phiên bản 11.

274. ### Content projection là gì?

     Content projection là một pattern trong đó bạn chèn, hoặc project, nội dung mà bạn muốn sử dụng bên trong một component khác.

275. ### ng-content là gì và mục đích của nó là gì?

     ng-content được sử dụng để chèn nội dung động bên trong component giúp tăng khả năng tái sử dụng component.

276. ### Standalone component là gì?

     Standalone component là một loại component không thuộc về bất kỳ Angular module nào. Nó cung cấp một cách đơn giản hóa để xây dựng ứng dụng Angular.

277. ### Làm thế nào để tạo một standalone component bằng lệnh CLI?

     Tạo một standalone component bằng lệnh CLI như sau:

     ```bash
     ng generate component component-name --standalone
     ```

     Khi chạy lệnh standalone component được tạo.
     Dưới đây là danh sách file được tạo.

     1. `component-name.component.ts`
     2. `component-name.component.css`
     3. `component-name.component.spec`
     4. `component-name.component.html`

     Tiếp theo cần cập nhật `app.module.ts` như dưới đây.

     ```typescript
     import { NgModule } from "@angular/core";
     import { BrowserModule } from "@angular/platform-browser";
     import { ComponentNameComponent } from "./component-name/component-name.component";

     @NgModule({
       imports: [BrowserModule, ComponentNameComponent],
       declarations: [AppComponent],
       bootstrap: [AppComponent],
     })
     export class AppModule {}
     ```

278. ### Làm thế nào để tạo một standalone component thủ công?

     Để làm cho component hiện có thành standalone, thêm `standalone: true` trong `component-name.component.ts`
     như dưới đây

     ```typescript
     import { CommonModule } from "@angular/common";
     import { Component, OnInit } from "@angular/core";

     @Component({
       standalone: true,
       imports: [CommonModule],
       selector: "app-standalone-component",
       templateUrl: "./standalone-component.component.html",
       styleUrls: ["./standalone-component.component.css"],
     })
     export class ComponentNameComponent implements OnInit {
       constructor() {}

       ngOnInit() {}
     }
     ```

     Tiếp theo cần cập nhật `app.module.ts` như dưới đây.

     ```typescript
     import { NgModule } from "@angular/core";
     import { BrowserModule } from "@angular/platform-browser";
     import { ComponentNameComponent } from "./component-name/component-name.component";

     @NgModule({
       imports: [BrowserModule, ComponentNameComponent],
       declarations: [AppComponent],
       bootstrap: [AppComponent],
     })
     export class AppModule {}
     ```

279. ### Hydration là gì?

     Hydration là quá trình khôi phục ứng dụng được render phía server trên client. Điều này bao gồm những việc như tái sử dụng cấu trúc DOM được render từ server, duy trì trạng thái ứng dụng, chuyển dữ liệu ứng dụng đã được lấy bởi server, và các quy trình khác.

     Để bật hydration, chúng ta phải bật server side rendering hoặc Angular Universal. Khi đã bật, chúng ta có thể thêm đoạn code sau vào root component.

     ```typescript
     import {
       bootstrapApplication,
       provideClientHydration,
     } from "@angular/platform-browser";

     bootstrapApplication(RootCmp, {
       providers: [provideClientHydration()],
     });
     ```

     Hoặc chúng ta có thể thêm `providers: [provideClientHydration()]` trong App Module

     ```typescript
     import { provideClientHydration } from "@angular/platform-browser";
     import { NgModule } from "@angular/core";
     @NgModule({
       declarations: [RootCmp],
       exports: [RootCmp],
       bootstrap: [RootCmp],
       providers: [provideClientHydration()],
     })
     export class AppModule {}
     ```

280. ### Angular Signals là gì?

     Signal là một wrapper xung quanh một giá trị có thể thông báo cho các consumer quan tâm khi giá trị đó thay đổi. Signals có thể chứa bất kỳ giá trị nào, từ các kiểu dữ liệu đơn giản đến các cấu trúc dữ liệu phức tạp.

281. ### Giải thích Angular Signals với một ví dụ.

     Trong ví dụ này, chúng ta tạo một signal có tên `count` và khởi tạo nó với giá trị 0. Sau đó chúng ta kết nối với signal, cho phép chúng ta được thông báo bất cứ khi nào giá trị của nó thay đổi. Cuối cùng, chúng ta thêm một nút để tăng count khi được click.

     Khi nút được click, phương thức `incrementCount()` được gọi. Phương thức này đặt giá trị mới của signal `count` thành 1. Các đối tượng được kết nối với signal (subscribers) sau đó được thông báo về sự thay đổi, và giá trị được cập nhật được hiển thị trong UI.

     Trong file TypeScript

     ```typescript
     import { Component, OnInit } from "@angular/core";
     import { signal, computed } from "@angular/core"; // Import from '@angular/core'

     @Component({
       selector: "my-app",
       templateUrl: "./app.component.html",
       styleUrls: ["./app.component.css"],
     })
     export class AppComponent implements OnInit {
       count = signal(0);
       doubleCount = computed(() => this.count() * 2);

       constructor() {}

       ngOnInit() {
         // Optional logging for debugging displayedCount changes
         // console.log('Displayed count changed to:', this.displayedCount());
       }

       incrementCount() {
         this.count.set(this.count() + 1);
       }

       decrementCount() {
         this.count.update((value) => Math.max(0, value - 1));
       }
     }
     ```

     Trong file HTML

     ```html
     <h1>Angular Signals Example</h1>

     <button (click)="incrementCount()" style="margin-right: 10px;">
       Increment Count
     </button>
     <button (click)="decrementCount()">Decrement Count</button>

     <p>Count: {{ count() }}</p>
     <p>Double Count: {{ doubleCount() }}</p>
     ```

282. ### Route Parameters là gì? Bạn có thể giải thích từng loại không?

     Route parameters được sử dụng để truyền các giá trị động trong URL của một route. Chúng cho phép bạn định nghĩa các phân đoạn biến trong đường dẫn route, có thể được truy cập và sử dụng bởi components và services. Path parameters được đại diện bởi dấu hai chấm (":") theo sau là tên tham số.

     Có ba loại route parameters trong Angular:

     **Path parameters:** Path parameters được sử dụng để định nghĩa các phân đoạn động trong đường dẫn URL. Chúng được chỉ định như một phần của đường dẫn của route và được trích xuất từ URL thực tế khi điều hướng đến route đó. Path parameters được đại diện bởi dấu hai chấm (":") theo sau là tên tham số. Ví dụ:

     ```typescript
     { path: 'users/:id', component: UserComponent }
     ```

     Trong ví dụ này, ":id" là path parameter. Khi điều hướng đến một URL như "/users/123", giá trị "123" sẽ được trích xuất và có thể được truy cập trong UserComponent.

     **Query parameters:** Query parameters được sử dụng để truyền thông tin bổ sung trong URL dưới dạng các cặp key-value. Chúng được thêm vào URL sau dấu hỏi ("?") và có thể được truy cập bởi components và services. Query parameters không phải là một phần của đường dẫn route, nhưng chúng cung cấp dữ liệu bổ sung cho route. Ví dụ:

     ```typescript
     { path: 'search', component: SearchComponent }
     ```

     Trong ví dụ này, một URL như "/search?query=angular" chứa một query parameter "query" với giá trị "angular". SearchComponent có thể lấy giá trị của query parameter và sử dụng nó để tìm kiếm.

     **Optional parameters:** Optional parameters được sử dụng khi bạn muốn làm cho một route parameter trở thành tùy chọn. Chúng được đại diện bằng cách đặt dấu hỏi ("?") sau tên tham số. Optional parameters có thể hữu ích khi bạn có các routes với các tham số khác nhau. Ví dụ:

     ```typescript
     { path: 'products/:id/:category?', component: ProductComponent }
     ```

     Trong ví dụ này, tham số ":category" là tùy chọn. ProductComponent có thể được truy cập với các URL như "/products/123" hoặc "/products/123/electronics". Nếu tham số ":category" có trong URL, nó sẽ có sẵn trong component, nếu không nó sẽ là undefined.

     Route parameters cung cấp một cách linh hoạt để xử lý dữ liệu động trong ứng dụng Angular của bạn. Chúng cho phép bạn tạo các routes có thể dễ dàng tùy chỉnh và cung cấp trải nghiệm người dùng liền mạch bằng cách phản ánh trạng thái hiện tại của ứng dụng trong URL.