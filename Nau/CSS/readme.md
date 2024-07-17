CSS gồm

1. Inline (CSS nội tuyến): <tag style="css" />
2. Internal (CSS nội bộ): <style>css</style>
3. External (CSS bên ngoài): <link href="style.css"/>
   Độ ưu tiên trong css:
   Inline --> Internal --> External(Internal và External ai viết đè trước thì code đó thực thi trước)
4. Color: màu
5. font-style:
   +italic: in nghiêng
6. font-size: cỡ chữ
7. font-family: font chữ
8. text-transform: viết hoa, viết thường
9. text-align: căn dòng
10. line-height: định khoảng cách giữa các dòng = x lần font chữ
11. background-image: là hình nền bên trong
12. max-width: chiều rộng lớn nhất được sử dụng
13. opacity: quy định độ trong suốt ( tương tác được, chiếm không gian, không nhìn thấy trên giao diện, hộ trợ animations)
    1: 0.0 --> 1.0 2. 0% --> 100% --> từ mờ nhất đến rõ nhất
14. display: none là ẩn phần tử ra khỏi giao diện (xóa cả không gian nó đang chiếm,không thể tương tác)
15. visibility: ẩn hoặc hiện element ( không tương tác được, chiếm không gian, không nhìn thấy trên giao điện, có tính kế thừa, hiển thị phần từ con,hộ trợ animations) 1. hidden: biến mất
16. visible: hiện
17. transition: là hiệu ứng animations ẩn trong thời gian bao nhiêu s
    background-img: url(./): đổi nền ảnh background
    <input type="checkbox" /> Click vào em đi đừng sợ <br /> nhập ô dữ liệu.
18. Favicon: logo trong web
19. Prefix: nhưng câu lệnh hộ trợ cho trình duyệt 19. user-select: không thể bôi đen; 20. Selector: là tham chiếu cho cái phần tử
    \*id: id="Nau" là duy nhất, không được trùng id #Nau là nhập bên css 21. class: có thể trùng nhau và linh động hơn class="item_ul1",.item_ul1 là nhập bên css
    - list-style-type: none là xóa đi giấu chấm trong list ul

\*\* là select cho toàn bộ nội dung trong body
div,p,... là chọn tất cả thẻ bên trong
.class1.class2 là chọn vô thẻ trong tên của class đó
div p là chọn tất cả thẻ nằm trong thẻ div
div > p là chọn tất cả thẻ p là con trực tiếp của thẻ div
div + p là chọn thẻ con p đầu tiên ngay sau thẻ div
div ~ p là chọn tất cả thẻ p nằm liền kề trong thẻ div

attribute: thuộc tính
[href]: chọn thuộc tính href để thay đổi
p[href]: chọn thẻ p có thuộc tính href để thay đổi

1. attribute=value
   [target="_blank"]: chọn thuộc tính target="blank" để thay đổi
2. attribute ~=value
   [title~="pic"]: chọn tất cả các thuộc tính: title có chưa từ pic trong giá trị
3. attribute _=value
   [title_="pic"]: chon tất cả các thuộc tính: title có chứa chuỗi pic trong giá trị
4. attribute |=value
   [title|="pic"]: chọn tất cả các thuộc tính: 1. title có từ duy nhất bắt đầu bằng từ pic
5. attribute|^=value
   [title^="pic"]: chọn tất cả các thuộc tính: 1. title có chuỗi bắt đầu bằng từ pic
6. attribute$=value
[title$="pic"]:chọn tất cả các thuộc tính: 1. title có chuỗi kết thúc bằng từ pic \* Pseudo-classes:Một lớp giả được sử dụng để định nghĩa một trạng thái đặc biệt của 1 phần tử

7. hover: là một pseudo-class được sử dụng để thay đổi kiểu của một phần tử khi người dùng đưa con trỏ chuột lên phần tử đó. Thường được áp dụng cho các liên kết (link), nút (button), và các phần tử có thể tương tác khác để cải thiện trải nghiệm người dùng.để thay đổi màu nền của một nút khi người dùng đưa chuột vào [selector:hover]
8. active là tác động lên các thẻ khi nhấn giữ chuột [a:active]
9. link là tác động lên các thẻ có liên kết chưa click vào [a:link]
10. visited là tác động lên các thẻ có liên kết đã click truy cập [a:visited]
11. empty: chọn các thẻ không có nội dung [a:empty] 6. target: chọn các thẻ và sẽ thay đổi nếu mình nhấn vô nó
12. first-child: chọn các thẻ là thẻ con đầu tiên [p:first-child] 9. last-child: chọn các thẻ là thẻ con cuối cùng [p:last-child]
13. nth-child(n): chọn các thẻ là thẻ con thứ n từ trên xuống [p:nth-child(2)]
14. nth-last-child(n): chọn acsc thẻ là thẻ con thứ n từ dưới lên [p:nth-last-child(2)]
15. only-child: chọn các thẻ là thẻ con duy nhất [p:only-child]
    \_odd là chọn các phần tử lẻ [p:nth-last-child(odd)]
    \_even là chọn các phần tử chẵn [p:nth-last-child(even)]
    \_xn + x là chọn các phần từ bất kì [p:nth-last-child(3n+1)]

<!-- n=0 -> 3*0 + 1 = 1 là phần tử 1 sẽ thay đổi
     n = 1 -> 3*1 + 1= 4 là phần tử 4 sẽ thay đổi-->

13. first-of-type là chọn các thẻ xuất hiện đầu tiên trong thẻ cha [p:first-of-type]
14. last-of-type là chọn các thẻ xuất hiện cuối cùng trong thẻ cha [p:last-of-type]
15. nth-of-type(n) là chọn các thẻ thứ n trong thẻ cha [p:nth-of-type(n)]
16. nth-last-of-type(n) là chọn các thẻ thứ n trong thẻ cha tính từ dưới đi lên [p:nth-last-of-type(n)]
17. only-of-type: chọn các thẻ xuất hiện duy nhất trong thẻ cha [p:only-of-type]
18. not(selector): chọn các thẻ trong đó loại trừ đi thẻ được được chọn (selector) để không tác động css [.top:not(p)]
    _Mức độ ưu tiên CSS Selector
    1.!important
    2.Inline style ( viết code trên HTML)
    3.ID(#) selector
    4.Class(.) hoặc pseudo-class(:) selector
    5.Element selector (h,p,li,div,...)
    6.Universal selector(_): Bộ chọn chung

- Box Model: mô hình hộp

1. Nội dung (width, height,...) -> hình ảnh, video, text,...
2. padding -> khoảng đệm nội dung và viền (không chứa nội dung)
   _ 2 đối số: 20px 30px ( trái, phải)
   _ 3 đối số: 10px 20px 30px ( trên, trái phải, dưới)
   \_ 4 đối số: 10px 20px 30px 40px ( trên, phải, dưới, trái)
3. border -> viền của phần tử (viền nét đứt, liền, ...)
   border: 10px solid blue
   độ rộng (width), kiểu viền(style), màu(color)
   _ solid -> đường nét liền
   _ dashed -> đường nét đứt
   _ Dotted -> viền là các chấm dot
   _ double -> viền 2 đường song song liền nhau
   _ groove -> viền 3d
   _ ridge -> viền 3D
   \_ inset -> viền 3D
   \_outset -> viền 3D

   radius: là phần đường tròn
   _ border-radius: 20px 30px (trên trái dưới phải,trên phải dưới trái)
   _ border-radius: 30px 50px 70px (trên trái, trên phải dưới trái, dưới phải)
   \_ border-radius: 30px 50px 70px 40pz(trên trái, trên phải, dưới phải, dưới trái)

4. margin -> khoảng cách với các phần tử liền kề khác
5. margin collage: là hiện tượng chồng lặp thuộc tính margin khi 2 phần tử liền kề cùng thiết lập margin với phần từ còn lại theo chiều dọc ( chiều ngang thì không bị )
   kích thước cao \* rộng 1 phần tử = content + padding + border (không bao gồm margin)
6. Outline: là đường viền bao quanh mép ngoài cùng của đối tượng
   - Không làm tăng thêm kích thước phần tử
   - Đơn giản nó chỉ là 1 vùng bao bên ngoài, chiếm cả vào phần margin
   - outlint-offset: cách viền border ra 1 khoảng
7. Box Model - box-szing: content-box và border-box(border-box được sử dụng nhìu hơn)

- Default CSS Values: Trình duyệt sẽ tự thêm vào các thuộc tính mặc định để hiện thị các thẻ cơ bản mà chúng ta đã học

- Inheritance - Kế thừa: Các phần từ con nhận được giá trị thuộc tính thừa kế từ phần tử cha
  1.  font-family
  2.  font-size
  3.  font-weight
  4.  font-style
  5.  color
  6.  line-height
  7.  letter-spacing
      ...

\*Reset CSS:

\*Block và Inline:

- display: block là chiều dọc
- display: inline là chiều ngang (trên 1 dòng)
  1.  không áp dụng cho padding-top, padding-bottom
  2.  margin-top, margin-bottom
  3.  width, height, min-width, min-height
      +display: inline - block là cả 2

* Css Units: Đơn vị trong css

  1.  px - Picture Element ( thành phần hình ảnh) - điểm ảnh là đơn vị cơ bản để do kích thước 1 hình ảnh kỹ thuật số (tuyệt đối)
  2.  % là đơn vị này so với kích thước phần cha ( tương đối)
  3.  vw là chiều rộng khung hình (viewport - phần hiện thị trên browser)
  4.  vh là chiều cao khung hình (viewport - phần hiện thị trên browser)
  5.  em là kích thước gấp 2 lần font chữ hiện tại (có kế thừa)
  6.  rem là kích thước gấp 3 lần font chữ root element( không kế thừa) nhưng lại nên sử dụng

* CSS color

* Font chữ trong css

  1.  font không có gai ở đầu chữ cái San serif
  2.  font có gai ở đầu serif
  3.  font có cùng đọ rộng Monospace
  4.  font-weight: độ dày của chữ ( thường 100- 900)
  5.  line-height: khoảng cách dòng
  6.  letter-spacing: tăng giảm khoảng cách giữa các ký tự
  7.  word-spacing: khoảng cách giữa các từ
  8.  text-align: căn lề
  9.  text-decoration: thêm dấu gạch

  10. text-indent: thụt lề
  11. text-transform:

      - capitalize: viết hoa chữ cái đầu tiên
      - lowercase: viết thường toàn bộ text
      - uppercase: viết hoa toàn bộ text

  12. white-spacing: Quy định về khoảng trắng

      - normal: trạng thái mặc định
      - nowrap: không xuống dòng ( kể cả chạm tới lề)
      - pre: giữ nguyên định dạng code, giống thẻ pre ( xuống dòng khi hết câu)
      - pre-line: Tất cả khoảng trắng thừa mỗi dòng trong nội dung văn bản sẽ bị loại bỏ, dòng mơi(xuống dòng) thì được giữ nguyên
      - pre-wrap: giữ nguyên định dạng code, xuông dòng khi khoảng trắng ko chưa dc từ đó

  13. word-break: khi đoạn text hoặc link quá dài, người dùng nhập liền nhau thì có thẻ gây vỡ giao diện vì text không bị xuống dòng -> có thể dùng thuộc tính word-break: break-all để bẻ xuông hàng
  14. text-shadow: bóng đổ text
  15. overflow:

      - visible (default): thuộc tính mặc định: hiện thị nội dung kể cả vượt box chứa
      - hidden: ẩn nội dung: khi nội dung vượt box chứa
      - scroll: tạo thanh cuộn: luôn hiển thị vùng thanh cuốn
      - auto:
        1.  Nếu nội dung ngắn -> không có scroll bar
        2.  Nếu nội dung vượt box chứa -> tự động sinh ra scroll bar

  16. overscroll-behavior: thuộc tính cho thanh cuộn

      - auto: kéo hết phần con thì phần cha tự kéo theo
      - contain: kéo hết phần con thì nhấn qua phần cha để kéo tiếp
      - none:

  17. scrollbar: quan trọng
      /_ width _/
      ::-webkit-scrollbar {
      width: 10px;
      }

/_ Track _/
::-webkit-scrollbar-track {
background: #f1f1f1;
}

/_ Handle _/
::-webkit-scrollbar-thumb {
background: #888;
}

/_ Handle on hover _/
::-webkit-scrollbar-thumb:hover {
background: #555;
}

18. text-overflow: tạo dấu

    - ellipsis: tạo dấu ...
      overflow: hidden;
      -webkit-line-clamp: 2;
      -webkit-box-orient: vertical;
      display: -webkit-box;

19. font awesome:
20. background-color
21. background-image: url();
22. background-repeat: no-repeat
    repeat-x: chiều ngang
    repeat-y: chiều dọc
    repeat: cả x và
23. background-size: contain  
     cover
24. background-position: vị trí ảnh
25. background-image: linear-gradient()
26. background-attachment:
    - scroll: Default - Ảnh sẽ tự động cuộn theo trình duyệt khi kéo lên xuống
    - fixed: Ảnh cố định khi kéo scroll lên xuống
    - local: Ảnh cố định trong cục bộ trong bố cục con
27. background-clip: Quy định vùng đổ nền
    - border-box: Default - Ảnh sẽ đổ vào full kích thước phần tử ( content + padding + border)
    - padding-box: Ảnh chỉ đổ đén padding
    - content-box: Ảnh chỉ đổ nền content
    - text: đổ màu nền trong phần text, không hiển thị phần trống ngoài text
28. background-origin: gốc của ảnh
29. backdrop-filter: làm mờ khung

- Clip-path:
  1.  tạo 1 vùng cắt, nội dung trong vùng cắt sẽ được hiển tị
  2.  nội dung ngoài vùng cắt sẽ bị ẩn đi
      - circle(): cắt hình tròn
      - inset(): cắt hình chữ nhật
      - polygon(): cắt hình đa giác
- Box-shadow: đổ bóng cho phần tử

- Pointer-event: quản lý con trỏ chuột có thểm bấm vào hoặc không bấm vào
  loading="lazy" là load a tử trc cho đỡ bị trễ

- Pseudo-element là phần tử giả

  1.  ::first-line : chọn dòng đầu tiên ( không sử dụng trong thẻ có display: block)
  2.  ::first-letter: chọn chữ cái đầu tiên trong các thẻ

  3.  ::selection: chọn vùng đang được bôi đen các thẻ

  4.  ::marker: chọn các điểm đánh dấu của các phần tử li

  5.  ::before: thêm phần tử vào đăng trước class box

  6.  ::after: thêm phần tử vào đằng sau class box

- Hàm calc():

  - Là mộ hàm trong Css cho phép thực hiện các phép tính đơn giản như \_,-, \*, /
  - Có thẻ sử dụng với tất cả các thược tính CSS về kích thước như là width, height, margin, padding, top, left, background-position,...

- CSS Variables: Khi giá trị css dùng đi dùng lại nhiều lần, ta có thể gán biến cho nó để tái sử dụng

  - :root là khai báo toàn trang or HTML{}
  - --tên_biến
  - var(tên_biến)

- CSS Position: thuộc tính postion cho phép điều chỉnh vị trí các phần tử trên trang web
  1.  Position: Static -> Đây là giá trị mặc định của postion
      -> Các phần tử HTML mà chúng tâ đã biết có vị trí cố định trên trang khi chưa can thiệp bằng CSS
  2.  Position: Relative -> Định vị so với vị trí ban đầu của nó 1 khoảng x:
      - left( cách lề trái ban đầu 1 khoảng x)
      - right( cách lề phải ban đầu 1 khoảng x)
      - top (cách lề trên ban đàu đàu 1 khoảng x)
      - bottom (cách lề dưới ban đầu 1 khoảng x)
        Tuy nhiên, không có bất kỳ không gian mới nào được tạo ra để chứa pần tử được định vị theo kiểu này, vì vậy các phần tử khác trong trang web vẫn có thể bị che khuất bởi phần tử được định vị theo kiểu relative
  3.  Position: Absolute -> Phần tử thực sự được đưa ra khỏi luồng ban đầu
      1. Nếu không có tổ tiên có position: relative thì phần tử được định vị theo top left corner webpage
      2.
