# Seminar-GitHub 
LỚP: CDTH19C - nhóm 5
HỒ KHÁNH DUY -
PHÙNG KHẢ HÀO -
NGUYỄN ĐỨC TOÀN -
NGUYỄN QUỐC TUẤN -
HUỲNH XUÂN THỊNH 
- GitHub là: một dịch vụ cung cấp kho lưu trữ mã nguồn Git dựa trên nền web cho các dự án phát triển phần mềm. GitHub cung cấp cả phiên bản trả tiền lẫn miễn phí cho các tài         khoản. Các dự án mã nguồn mở sẽ được cung cấp kho lưu trữ miễn phí.
- GitHub được coi là một mạng xã hội dành cho lập trình viên lớn nhất và dễ dùng nhất với các tính năng cốt lõi như:
  + Wiki, issue, thống kê, đổi tên project, project được đặt vào namespace là user
  + Watch project: theo dõi hoạt động của project của người khác. Xem quá trình người ta phát triển phầm mềm thế nào, project phát triển ra sao
  + Follow user: theo dõi hoạt động của người khác
- Có 2 cách tiếp cận GitHub: Tạo project của riêng mình Contribute cho project có sẵn: fork project có sẵn của người khác, sửa đổi, sau đó đề nghị họ cập nhật sửa đổi của mình     
- Một vài khái niệm của Git cần nắm
  + git: là prefix của các lệnh được sử dụng dưới CLI
  + branch: được hiểu như là nhánh, thể hiện sự phân chia các version khi 2 version đó có sự sai khác nhất định và 2 version đều có sự khác nhau
  + commit: là một điểm trên cây công việc (Work Tree ) hay gọi là cây phát triển công việc
  + clone: được gọi là nhân bản, hay thực hiện nhân bản. Sử dụng để clone các project, repository trên các hệ thống chạy trên cơ sở là git, ví dụ như: bitbucket, github, gitlab,       cor(1 sản phẩm mã nguồn mở cho phép người dùng tự tạo git server cho riêng mình trên vps, server),… Việc clone này sẽ sao chép repository tại commit mình mong muốn, dùng để       tiếp tục phát triển. Thao tác này sẽ tải toàn bộ mã nguồn, dữ liệu về máy tính của bạn
  + repository: Kho quản lý dữ liệu, là nơi lưu trữ các dữ liệu, mã nguồn của project
  + remote: sử dụng để điều khiển các nhánh từ một repository trên git server, đối xử với các nhánh trên remote tương tự như đối xử với các nhánh trên local
- Lợi ích của Github đối với lập trình viên
  + Quản lý source code dễ dàng: Khi bạn tạo một repo, toàn bộ source code của repo đó được lưu trên GitHub. Tại đây, bạn có thể coi lại quá trình mình đã làm việc thông qua các       comment sau mỗi lần commit. Và cái hay ở đây, là nhiều người có thể cùng làm một repo. Lợi ích đầu tiên, chính là bạn biết được ai đã commit và commit cái gì. Tiếp theo,           source của bạn có thể phát triển theo nhiều nhánh. Nguyên tắc làm việc với các nhánh như thế này: Bạn có thể rẽ nhiều nhánh để phát triển project. Nhưng cuối cùng, bạn phải       merge lại vào nhánh MASTER để ra được project hoàn chỉnh.
  + Theo dõi sự thay đổi của dự án qua các lần thay đổi: Khi có nhiều member cùng thực hiện một dự án thì khá là phức tạp để theo dõi revisons – ai thay đổi cái gì, lúc nào và mấy     cái files đó được stored ở đâu. Đừng lo vì GitHub đã tính đến chuyện này giúp bạn, bằng cách luôn lưu lại những thay đổi bạn đã push lên repository. Cũng tương tự với             Microsoft Word hay Google Drive, bạn có một lịch sử phiên bản để phòng trường hợp các phiên bản trước đó bị mất hay không được lưu
  + Markdown: Markdown là một cách định dạng text trên web. Bạn có thể chỉnh sửa cách hiển thị của document, format từ như định dạng in đậm hay in nghiêng, thêm hình và tạo list       những thứ bạn có thể làm với Markdown. Hầu hết, Markdown chỉ là đoạn text đơn thuần với những ký tự đặc biệt chèn vào, như # hay *. Trong GitHub thì bạn có thể sử dụng Mardown     ở những nơi: Git, Comments tại Issues và Pull Requests, các file có đuôi .md hay .markdown extension
- Github là một kho tài nguyên tuyệt vời: Với chức năng Explore, bạn có thể theo dõi, tìm kiếm những open source projects theo đúng technology pattern mà bạn ưa thích. Github hỗ     trợ code search không kể nó ở dưới dạng một project riêng biệt hay là website. Ngoài ra, nền tảng này cũng có SEO khá tốt nên người dùng có thể tìm kiếm bất kỳ code string nào     được chia sẻ public
- Github Package Registry: Cái package registry này cho phép lập trình viên duy trì distribution registries của họ, bao gồm npm, docker, maven, nuget và Ruby gems. Đừng ngần ngại   mà không tạo ngay cho mình một tài khoản Github. Tạo những project của riêng mình và chia sẻ với mọi người, hoặc bạn có thể thoải mái fork một project của một open source nào     đó. Tạo pull request hoặc issues nếu như tìm được lỗi, cần support
- Mở rộng mối quan hệ
  + Gặp gỡ những dev mới: Vài ngàn developer toàn cầu đang tham gia mạng lưới rộng lớn của GitHub để chia sẻ kinh nghiệm của họ cũng như những ý tưởng rất đỉnh
  + Chia sẻ kinh nghiệm bản thân: Git cho phép user share code, text fragments hay bất kỳ thông tin nào với các dev khác. Do đó bạn có thể dùng nó để trao đổi text, hay gists       work như git repositories, từ đó tách ra và update các phiên bản đó
