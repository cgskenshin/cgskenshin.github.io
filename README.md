<!DOCTYPE html>
<html>
<!-- Liên kết css -->
<link rel="stylesheet" href="css_lab4.css">

<head>
    <!-- Mô tả trang -->
    <title>Lab 4</title>
</head>

<body>
    <!-- Tiêu đề -->
    <div id="tieuDe">
        <p>WEB1013 - PT163010</p>
        <p id="phuDe">TABLE OF CONTENT</p>
    </div>
    <!-- Mục Lục -->
    <div id="MucLuc">
        <ul id="ul1">
            <!-- WEB1013 - PT163010 -->
            <li>
                <a href="#tieuDe">
                    <h3>WEB1013 - PT163010</h3>
                </a>
            </li>
            <!-- Prerequisites -->
            <li>
                <a href="#phongChuLon">
                    <h4>Prerequisites</h4>
                </a>
            </li>
            <!-- HTML -->
            <li>
                <a href="#HTML">
                    <h4>HTML</h4>
                </a>
                <ul id="ul2">
                    <!-- Basic concept -->
                    <li>
                        <a href="#Basic_concept1">
                            <h5>Basic concept</h5>
                        </a>
                    </li>
                    <!-- Version -->
                    <li>
                        <a href="#Version1">
                            <h5>Version</h5>
                        </a>
                    </li>
                    <!-- Structure -->
                    <li>
                        <a href="#Structure">
                            <h5>Structure</h5>
                        </a>
                    </li>
                    <!-- Basic tags -->
                    <li>
                        <a href="#Basic_tags">
                            <h5>Basic tags</h5>
                        </a>
                    </li>
                </ul>
            </li>
            <!-- CSS -->
            <li>
                <a href="#CSS">
                    <h4>CSS</h4>
                </a>
                <ul id="ul2">
                    <!-- Basic concept -->
                    <li>
                        <a href="#Basic_concept2">
                            <h5>Basic concept</h5>
                        </a>
                    </li>
                    <!-- Version -->
                    <li>
                        <a href="#Version2">
                            <h5>Version</h5>
                        </a>
                    </li>
                    <!-- Syntax -->
                    <li>
                        <a href="#Syntax">
                            <h5>Syntax</h5>
                        </a>
                    </li>
                    <!-- How to? -->
                    <li>
                        <a href="#How_to?">
                            <h5>How to?</h5>
                        </a>
                    </li>
                    <!-- Priority -->
                    <li>
                        <a href="#Priority">
                            <h5>Priority</h5>
                        </a>
                    </li>
                    <!-- Box Model -->
                    <li>
                        <a href="#Box_Model">
                            <h5>Box Model</h5>
                        </a>
                    </li>
                    <!-- Position -->
                    <li>
                        <a href="#Position">
                            <h5>Position</h5>
                        </a>
                    </li>
                </ul>
            </li>
            <!-- Web Utility -->
            <li>
                <a href="#Web_Utility">
                    <h4>Web Utility</h4>
                </a>
            </li>
            <!-- Hosting -->
            <li>
                <a href="#Hosting">
                    <h4>Hosting</h4>
                </a>
            </li>
        </ul>
    </div>
    <!-- Nội Dung -->
    <div id="NoiDung">
        <ol>
            <!-- Prerequisites -->
            <li>
                <h2 id="phongChuLon">Prerequisites</h2>
                <ul>
                    <!-- Client & Server -->
                    <li id="star">
                        <p id="phongChuNho">Client & Server</p>
                    </li>
                    <!-- Request & Response -->
                    <li id="star">
                        <p id="phongChuNho">Request & Response</p>
                    </li>
                    <!-- Browser -->
                    <li id="star">
                        <p id="phongChuNho">Browser</p>
                    </li>
                </ul>
            </li>
            <img src="anh.png" width="50%" height="50%">
            <!-- HTML -->
            <li>
                <h2 id="phongChuLon"><p id="HTML">HTML</p></h2>
                <ul id="ul2">
                    <!-- Basic concept -->
                    <li id="star">
                        <p id="phongChuNho"><p id="Basic_concept1">Basic concept</p>
                        <ul>
                            <!-- Purpose -->
                            <li id="circle">
                                <p class="Mini">Purpose</p>
                                <p class="vietthem">Thao tác web</p>
                            </li>
                            <!-- Definition -->
                            <li id="circle">
                                <p class="Mini">Definition</p>
                                <p class="vietthem">Siêu văn bản</p>
                            </li>
                        </ul>
                    </li>
                    <!-- Version -->
                    <li id="star">
                        <p id="phongChuNho"><p id="Version1">Version</p></p>
                        <p>HTML</p>
                    </li>
                    <!-- Structure -->
                    <li id="star">
                        <p id="phongChuNho"><p id="Structure">Structure</p></p>
                        <ul>
                            <!-- Tag -->
                            <li id="circle">
                                <p class="Mini">Tag</p>
                                <p class="vietthem">3 phần chính: thẻ mở, nội dung, thẻ đóng</p>
                            </li>
                            <!-- Web page & Website -->
                            <li id="circle">
                                <p class="Mini">Web page & Website</p>
                                <ul>
                                    <!-- Doctype -->
                                    <li>
                                        <p>Doctype</p>
                                        <p class="vietthem"> Thông báo cho trình duyệt của khách truy cập trang web rằng tài liệu được hiển thị là tài liệu HTML</p>
                                    </li>
                                    <!-- Head (Metadata) -->
                                    <li>
                                        <p>Head (Metadata)</p>
                                        <p class="vietthem">Là bộ chứa siêu dữ liệu.</p>
                                    </li>
                                    <!-- Body -->
                                    <li>
                                        <p>Body</p>
                                        <p class="vietthem">Xác định phần thân của một tài liệu HTML.</p>
                                    </li>
                                </ul>
                            </li>
                        </ul>
                    </li>
                    <li id="star">
                        <p id="phongChuNho"><p id="Basic_tags">Basic tags</p></p>
                        <table border="1" cellspacing="0" cellpadding="5" style="margin-right: 100px;">
                            <!--Dòng tiêu đề: Đổi màu nền trong hàng-->
                            <tr class="Nen1">
                                <!--Tạo ô tiêu đề trong hàng-->
                                <th>Tag Syntax</th>
                                <th>Tag Name</th>
                                <th>Description</th>
                                <th>Example</th>
                            </tr>
                            <!--h1 - h6-->
                            <tr class="Nen2">
                                <!--Tạo ô bình thường trong hàng-->
                                <td>h1 - h6</td>
                                <td>Heading</td>
                                <td>Tạo tiêu đề trong cấu trúc trang web</td>
                                <td><a href="https://carly.com.vn/media/1131/the-heading-la-gi.png">Click</a></td>
                            </tr>
                            <!--p-->
                            <tr class="Nen3">
                                <td>p</td>
                                <td>Paragraphs</td>
                                <td>Tạo một đoạn văn mới</td>
                                <td><a href="https://www.w3resource.com/w3r_images/html-p-tag.png">Click</a></td>
                            </tr>
                            <!--span-->
                            <tr class="Nen2">
                                <td>span</td>
                                <td>Span</td>
                                <td>Định dạng nội dung</td>
                                <td><a href="https://static.javatpoint.com/htmlpages/images/htmlspantag.png">Click</a>
                                </td>
                            </tr>
                            <!--ul-->
                            <tr class="Nen3">
                                <td>ul</td>
                                <td>Ul</td>
                                <td>Để tạo danh sách không có thứ tự.</td>
                                <td><a
                                        href="https://www.w3docs.com/uploads/media/default/0001/01/3b29b697c81407acb8327bf06b9d1e0a8f98ac7a.png">Click</a>
                                </td>
                            </tr>
                            <!--li-->
                            <tr class="Nen2">
                                <td>li</td>
                                <td>Li</td>
                                <td>Tạo mục trong danh sách</td>
                                <td><a
                                        href="https://clarkwp.files.wordpress.com/2013/10/lists_and_nested_lists_in_wordpress.png?w=311">Click</a>
                                </td>
                            </tr>
                            <!--a-->
                            <tr class="Nen3">
                                <td>a</td>
                                <td>Hyperlink</td>
                                <td>Tạo một siêu liên kết từ trang này tới trang khác</td>
                                <td><a href="https://www.w3.org/Style/Examples/011/snapshot11.png">Click</a></td>
                            </tr>
                            <!--img-->
                            <tr class="Nen2">
                                <td>img</td>
                                <td>Image</td>
                                <td>Chèn ảnh</td>
                                <td><a href="https://s1.o7planning.com/en/12441/images/44541004.png">Click</a></td>
                            </tr>
                            <!--table-->
                            <tr class="Nen3">
                                <td>table</td>
                                <td>Tables</td>
                                <td>Tạo bảng</td>
                                <td><a href="https://i.imgur.com/uIwzEfS.png">Click</a></td>
                            </tr>
                            <!--input-->
                            <tr class="Nen2">
                                <td>input</td>
                                <td>Input</td>
                                <td>Sử dụng để nhập hay chọn thông tin</td>
                                <td><a
                                        href="https://www.wikitechy.com/step-by-step-html-tutorials/img/html-images/code-explanation-input-tag-in-html.png">Click</a>
                                </td>
                            </tr class="Nen3">
                            <!--button-->
                            <tr class="Nen3">
                                <td>button</td>
                                <td>Button</td>
                                <td>Dùng để tạo nút bấm</td>
                                <td><a href="https://miro.medium.com/max/1000/0*mhWBVfsSe6osUIKU.jpg">Click</a></td>
                            </tr>
                            <!--from-->
                            <tr class="Nen2">
                                <td>from</td>
                                <td>From</td>
                                <td>Xác định một biểu mẫu</td>
                                <td><a href="https://www.webtrainingroom.com/blogimages/html-form.png">Click</a></td>
                            </tr>
                            <!--div-->
                            <tr class="Nen3">
                                <td>div</td>
                                <td>Div</td>
                                <td>Sử dụng để phân khu vực</td>
                                <td><a
                                        href="https://cs.wellesley.edu/~cs110/reading/div-span-id-class-files/div_id.png">Click</a>
                                </td>
                            </tr>
                        </table>
                    </li>
                </ul>
            </li>
            <!-- CSS -->
            <li>
                <h2 id="phongChuLon"><p id="CSS">CSS</p></h2>
                <ul id="ul2">
                    <!-- Basic concept -->
                    <li id="star">
                        <p id="phongChuNho"><p id="Basic_concept2">Basic concept</p></p>
                        <ul>
                            <!-- Purpose -->
                            <li id="circle">
                                <p class="Mini">Purpose</p>
                                <p class="vietthem">Tạo kiểu cho trang web.</p>
                            </li>
                            <!-- Definition -->
                            <li id="circle">
                                <p class="Mini">Definition</p>
                                <p class="vietthem">Ngôn ngữ định kiểu.</p>
                            </li>
                        </ul>
                    </li>
                    <!-- Version -->
                    <li id="star">
                        <p id="phongChuNho"><p id="Version2">Version</p></p>
                    </li>
                    <!-- Syntax -->
                    <li id="star">
                        <p id="phongChuNho"><p id="Syntax">Syntax</p></p>
                        <ul>
                            <!-- Selector -->
                            <li id="circle">
                                <p class="Mini">Selector</p>
                                <p class="vietthem">Cho phép nhắm mục tiêu tới các phần từ HTML.</p>
                            </li>
                            <!-- Declaration -->
                            <li id="circle">
                                <p class="Mini">Declaration</p>
                                <p class="vietthem"></p>Selector và property trong ngoặc nhọn</p>
                            </li>
                            <!-- Unit -->
                            <li id="circle">
                                <p class="Mini">Unit</p>
                                <p class="vietthem">Đơn vị tuyệt đối (absolute) và đơn vị tương đối (reletive)</p>
                            </li>
                        </ul>
                    </li>
                    <!-- How to? -->
                    <li id="star">
                        <p id="phongChuNho"><p id="How_to?">How to?</p></p>
                        <ul>
                            <!-- Inline -->
                            <li id="circle">
                                <p class="Mini">Inline</p>
                                <p class="vietthem">Được sử dụng trong một thẻ nhất định.</p>
                            </li>
                            <!-- Internal -->
                            <li id="circle">
                                <p class="Mini">Internal</p>
                                <p class="vietthem">Được đặt trong phần mở đầu của html.</p>
                            </li>
                            <!-- External -->
                            <li id="circle">
                                <p class="Mini">External</p>
                                <p class="vietthem">Liên kết website với file .css</p>
                            </li>
                        </ul>
                    </li>
                    <!-- Priority -->
                    <li id="star">
                        <p id="phongChuNho"><p id="Priority">Priority</p></p>
                        <p class="vietthem">Class < Id < Inline < Internal=External</p>
                    </li>
                    <!-- Box Model -->
                    <li id="star">
                        <p id="phongChuNho"><p id="Box_Model">Box Model</p></p>
                        <p class="vietthem">Content, padding, border, margin</p>
                    </li>
                    <!-- Position -->
                    <li id="star">
                        <p id="phongChuNho"><p id="Position">Position</p></p>
                        <p class="vietthem">Ralative, absolute, fixed, inherit</p>
                    </li>
                </ul>
            </li>
            <!-- Web Utility -->
            <li>
                <h2 id="phongChuLon"><p id="Web_Utility">Web Utility</p></h2>
                <ul>
                    <!-- Purpose -->
                    <li id="star">
                        <p>Purpose</p>
                    </li>
                    <!-- Sample utilities -->
                    <li id="star">
                        <p>Sample utilities</p>
                    </li>
                </ul>
            </li>
            <!-- Hosting -->
            <li>
                <h2 id="phongChuLon"><p id="Hosting">Hosting</p></h2>
                <ul>
                    <!-- Basic concept -->
                    <li id="star">
                        <p id="phongChuNho">Basic concept</p>
                    </li>
                    <!-- Host -->
                    <ul id="star">
                        <li id="circle">
                            <p class="Mini">Host</p>
                        </li>
                        <!-- Domain -->
                        <li id="circle">
                            <p class="Mini">Domain</p>
                        </li>
                        <!-- DNS -->
                        <li id="circle">
                            <p class="Mini">DNS</p>
                        </li>
                    </ul>
                    <!-- Registration service -->
                    <li id="star">
                        <p id="phongChuNho">Registration service</p>
                    </li>
                    <!-- Website uploading -->
                    <li id="star">
                        <p id="phongChuNho">Website uploading</p>
                    </li>
                    <!-- Website management -->
                    <li id="star">
                        <p id="phongChuNho">Website management</p>
                    </li>
                </ul>
            </li>
        </ol>
    </div>
    <!-- Tác giả -->
    <div id="author">
        <!-- Ảnh -->
        <div id="avt">
            <img src="https://i.imgur.com/WbjFynJ.png" width="10%" height="10%">
        </div>
        <!-- Thông tin -->
        <div id="info">
            <h3>Nguyễn Trung Thinh - ThinhNTPH17784</h3>
            <h4>Lớp - PT163010</h4>
        </div>
    </div>
        <!-- Load Facebook SDK for JavaScript -->
      <div id="fb-root"></div>
      <script>
        window.fbAsyncInit = function() {
          FB.init({
            xfbml            : true,
            version          : 'v9.0'
          });
        };

        (function(d, s, id) {
        var js, fjs = d.getElementsByTagName(s)[0];
        if (d.getElementById(id)) return;
        js = d.createElement(s); js.id = id;
        js.src = 'https://connect.facebook.net/vi_VN/sdk/xfbml.customerchat.js';
        fjs.parentNode.insertBefore(js, fjs);
      }(document, 'script', 'facebook-jssdk'));</script>

      <!-- Your Chat Plugin code -->
      <div class="fb-customerchat"
        attribution="setup_tool"
        page_id="176481772765806"
  theme_color="#fa3c4c"
  logged_in_greeting="Xin chào, Chúng tôi có thể giúp gì cho bạn?"
  logged_out_greeting="Xin chào, Chúng tôi có thể giúp gì cho bạn?">
      </div>
    </div>
</body>

</html>
