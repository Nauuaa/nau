cấu trúc file html
Doctype
thẻ html
thẻ head
thẻ body

attribute(thuộc tính):
thẻ h1 -> h6: tiêu đề
    <h1></h1>
thẻ p: văn bản
    <p></p>
thẻ hr: gạch ngang
    <hr>
thẻ br: xuống dòng
    <br>
thẻ b: in chữ đậm
    <b></b>
thẻ i: in chữ nghiêng
    <i></i>
thẻ u: in chữ gạch dưới
    <u></u>
thẻ ul: danh sách không có thứ tự
    <ul></ul>
thẻ ol: danh sách có thứ tự
    <ol reversed>: đảo ngược số
    <ol type="">: thay đổi chữ số
thẻ li: thẻ con trực tiếp của ul, ol
thẻ a: gắn link
    <a href="">Tải lại trang</a>
    <a href="#">Trở lên đầu trang</a>
        +Một số thuộc tính cơ bản của target
        <a href="" target="_self"></a>
        <a href="">Mở tại trang hiện tại</a>
        <a href="" target="_blank">Mở trong tab mới</a>
        +Liên kết tới số điện thoại
        <a href="tel:0395438625"></a>
        <a href="tel:+84395438625"></a>
        +Liên kết tới số email: mailto
        <a href="mailto:lequocduy753@gmail.com"></a>
            1 số tham số có thể truyền trước cho: mailto 
                cc: danh sách email sẽ nhận được bản sao của thư
                bcc: danh sách email ẩn sẽ nhận được bản sao của thư
                subject: chủ đề của thư
                ?: dấu phân cách giữa phần mailto và tham số
                &: dấu phân cách tham số
                ,: là thêm tham số
                <a href="mailto:lequocduy753@gmail.com?cc=lequocduy753@gmail.com &subject=helpme"></a>
thẻ img: hình ảnh
      <img src="" alt="">
*HTML PATH: đường dẫn 
    ./ là đường dẫn tương đối
    ../ trở về thư mục trên 1 cấp
*HTML Entities:
thẻ pre: thẻ để giữ văn bản giữ nguyên
<pre></pre>
thẻ code: thẻ giữ nguyên ngữ nghĩa 
  <code></code>
thẻ table: thẻ bảng
  <table></table>
    tr: Table Row: đại diện cho một hàng trong bảng HTML
    <tr></tr>
    td: Table Data: Định nghĩa một ô dữ liệu trong một bảng
    <td></td>
    th: Table Header: Định nghĩa một ô tiêu đề trong bảng
    <th></th>
    thead: Table Header : Định nghĩa phần đầu bảng
        <thead></thead>
    tbody: Table Body: Định nghĩa phần thân bảng
        <tbody></tbody>
    tfoot: Table Footer: Định nghĩa phần cuối bảng
        <tfoot></tfoot>
    Cosplan: chỉ định phần tử chiếm bao nhiêu cột

    Rowspan: chỉ định phần tử chiếm bao nhiêu hàng


