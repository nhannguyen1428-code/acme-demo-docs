# Cách đặt mức tồn kho tối thiểu cho cửa hàng nhỏ

Nhiều cửa hàng tạp hoá, mỹ phẩm hay vật tư nhỏ đang đặt mức tồn kho tối thiểu theo cảm tính. Ví dụ, thấy sữa tắm bán cũng được thì đặt ngưỡng 10 chai, dầu gội thì 5 chai. Kết quả là hàng bán chạy vẫn hết đúng lúc khách hỏi nhiều, còn hàng chậm luân chuyển thì chất đầy kệ, đọng vốn.

Gốc rễ của vấn đề nằm ở chỗ một con số cố định không phản ánh ba yếu tố luôn thay đổi: tốc độ bán thực tế, thời gian nhập hàng thực tế và biến động theo mùa. Mỗi mã hàng có một nhịp bán và một chuỗi cung ứng riêng. Vì vậy, mức tồn kho tối thiểu không nên là một con số đặt một lần rồi để đó. Nó là một quy trình ba bước có thể làm xong trong một buổi chiều, với dữ liệu bán hàng sẵn có trong sổ tay hoặc Excel.

## Bước 1 — Tính tốc độ bán trung bình mỗi ngày cho từng mã hàng

Không nên bắt đầu bằng việc hỏi “nên để bao nhiêu”. Hãy bắt đầu bằng việc nhìn lại dữ liệu bán thực tế.

Lấy dữ liệu bán trong 4–8 tuần gần nhất từ sổ tay, hoá đơn hoặc file Excel. Với mỗi mã hàng, tính tổng số lượng đã bán trong kỳ, rồi chia cho số ngày của kỳ.

Công thức:

**Tốc độ bán/ngày = tổng số bán trong kỳ ÷ số ngày của kỳ**

Giả sử một mã sữa rửa mặt bán được 120 tuýp trong 60 ngày. Tốc độ bán là 2 tuýp mỗi ngày.

Không cần làm ngay cho toàn bộ danh mục. Ưu tiên nhóm hàng bán chạy trước, thường là khoảng 20–30% mã hàng đóng góp phần lớn doanh số. Đây cũng là nhóm gây thiệt hại rõ nhất khi hết hàng.

Một lưu ý quan trọng: loại bỏ những ngày bán bất thường khỏi dữ liệu tính. Ví dụ ngày khuyến mãi mạnh, ngày có khách mua sỉ đột xuất. Nếu không loại, tốc độ bán bị đẩy lên cao, dẫn đến đặt ngưỡng quá lớn và ôm hàng.

## Bước 2 — Cộng thời gian nhập hàng và độ trễ thực tế để ra ngưỡng tối thiểu ban đầu

Tốc độ bán cho biết mỗi ngày trôi qua cần bao nhiêu hàng. Tiếp theo, cần xác định khoảng thời gian từ lúc quyết định nhập đến lúc hàng lên kệ bán được.

Thời gian nhập hàng thực tế gồm ba phần:

- Thời gian đặt hàng: từ lúc phát hiện sắp hết đến lúc gọi điện, nhắn tin cho nhà phân phối.
- Thời gian giao hàng: từ lúc nhà phân phối xác nhận đến lúc hàng về tới cửa hàng.
- Thời gian kiểm hàng và lên kệ: từ lúc nhận hàng đến lúc hàng sẵn sàng bán.

Đừng dùng con số nhà phân phối hứa hẹn. Ví dụ họ nói giao trong 1–3 ngày, nhưng vào dịp lễ, Tết thường trễ thêm 2–3 ngày. Hãy ghi lại ngày đặt và ngày nhận thực tế trong vài lần nhập đầu tiên để có con số trung bình đáng tin.

Công thức:

**Ngưỡng tối thiểu ban đầu = tốc độ bán/ngày × tổng thời gian nhập hàng thực tế**

Tiếp tục ví dụ trên: tốc độ bán 2 tuýp/ngày, tổng thời gian nhập hàng thực tế là 5 ngày. Ngưỡng tối thiểu ban đầu là 10 tuýp.

Khi đặt hàng, nhớ làm tròn lên theo đơn vị đóng gói. Nếu nhập theo lốc 6 tuýp, 10 tuýp nên làm tròn thành 2 lốc, tức 12 tuýp.

## Bước 3 — Thêm vùng đệm an toàn theo biến động và mùa vụ

Ngưỡng tính ở bước 2 chỉ đủ cho điều kiện lý tưởng. Thực tế có biến động: có tuần khách mua nhiều hơn bình thường, có đợt nhà phân phối giao trễ. Vì vậy cần thêm một vùng đệm an toàn.

**Vùng đệm = tốc độ bán/ngày × số ngày đệm**

Số ngày đệm thường là 2–4 ngày cho hàng ổn định. Với hàng có nhu cầu thất thường, có thể cần 5–7 ngày.

Điều chỉnh theo mùa là bắt buộc. Với cửa hàng tạp hoá, mỹ phẩm ở đô thị Việt Nam, các dịp lễ, Tết thường làm tốc độ bán tăng mạnh. Nên nâng ngưỡng tối thiểu trước mùa cao điểm từ 2–4 tuần. Ví dụ trước Tết, sữa tắm, dầu gội, bánh kẹo thường bán nhanh hơn ngày thường đáng kể.

Phân nhóm hàng theo mức ưu tiên giúp đặt đệm hợp lý:

- Nhóm A: hàng bán chạy, không được hết. Đặt đệm dày, ví dụ 3–4 ngày.
- Nhóm B: hàng bán trung bình. Đặt đệm vừa, khoảng 2–3 ngày.
- Nhóm C: hàng chậm luân chuyển. Đặt đệm mỏng hoặc chỉ giữ ngưỡng tối thiểu thấp để tránh đọng vốn.

Giả sử mã sữa rửa mặt thuộc nhóm A, cộng 3 ngày đệm. Ngưỡng cuối cùng là 2 × (5 + 3) = 16 tuýp. Làm tròn theo lốc 6 sẽ là 3 lốc, tức 18 tuýp.

Ghi ngưỡng cuối cùng vào một bảng duy nhất theo mã hàng, kèm ngày rà soát để không bị bỏ quên.

## Bước 4 — Đưa ngưỡng vào phần mềm quản lý kho để tự động cảnh báo

Sau khi có bảng ngưỡng, việc còn lại là biến nó thành công cụ cảnh báo hằng ngày thay vì phải dò sổ tay.

Nếu đang dùng [Acme](https://acme.example/vi/quan-ly-kho), hãy nhập ngưỡng tối thiểu cho từng mã hàng vào hệ thống. Thiết lập quy tắc cảnh báo: khi tồn kho chạm hoặc thấp hơn ngưỡng, hệ thống sẽ đánh dấu hoặc gửi thông báo. Gắn cảnh báo với danh sách đặt hàng để nhân viên biết ngay cần nhập mã nào, số lượng bao nhiêu.

Với cửa hàng chưa dùng phần mềm, có thể dùng Excel với định dạng có điều kiện làm bước đệm. Tạo cột “Tồn hiện tại”, cột “Ngưỡng tối thiểu”, rồi đặt quy tắc tô đỏ khi tồn nhỏ hơn hoặc bằng ngưỡng. Cách này đơn giản nhưng vẫn giúp nhìn nhanh danh sách cần nhập.

Phân công một người kiểm tra danh sách cảnh báo vào giờ cố định mỗi ngày hoặc mỗi tuần. Với cửa hàng một đến ba nhân viên, nên chọn một khung giờ ít khách, ví dụ đầu giờ sáng hoặc cuối giờ chiều.

## Kiểm tra và hiệu chỉnh sau 4–8 tuần

Ngưỡng tối thiểu không phải là thứ đặt xong rồi để yên. Sau 4–8 tuần, cần nhìn lại hai chỉ số:

- Số lần hết hàng ở nhóm A và B.
- Lượng vốn tồn kho trung bình.

Nếu hàng bán chạy vẫn hết lặp lại, hãy tăng vùng đệm hoặc kiểm tra lại thời gian nhập hàng thực tế. Có thể nhà phân phối giao trễ hơn so với ghi nhận ban đầu.

Nếu vốn tồn tăng mà không có lý do, hãy giảm đệm ở nhóm C, hoặc xem lại tốc độ bán đã tính có bị phóng đại vì ngày khuyến mãi hay không.

Đặt lịch rà soát ngưỡng định kỳ mỗi quý và trước các mùa cao điểm. Riêng dịp Tết nên rà soát trước ít nhất một tháng.

## Lỗi thường gặp và cách tránh

- **Dùng chung một ngưỡng cho mọi mã hàng**: Mỗi nhóm ưu tiên có đệm khác nhau. Hãy tính riêng theo nhóm A, B, C.
- **Lấy thời gian giao hàng lý thuyết thay vì thực tế**: Ghi lại ngày đặt và ngày nhận thực trong vài lần nhập đầu để có con số đáng tin.
- **Quên điều chỉnh mùa vụ**: Đánh dấu trước các mốc lễ, Tết trên lịch rà soát và nâng ngưỡng trước mùa cao điểm.
- **Đặt ngưỡng quá thấp vì sợ đọng vốn**: Hàng bán chạy hết hàng còn gây thiệt hại hơn là giữ thêm vài ngày đệm. Với nhóm A, thà dư nhẹ còn hơn thiếu.
- **Không phân công người theo dõi cảnh báo**: Cảnh báo chỉ có giá trị khi có người xem và hành động đều đặn.

## Tóm tắt các bước trong một khung kiểm tra nhanh

1. Chọn 20–30% mã hàng bán chạy nhất để tính trước.
2. Tính tốc độ bán/ngày từ dữ liệu 4–8 tuần, loại ngày bán bất thường.
3. Xác định tổng thời gian nhập hàng thực tế gồm đặt hàng, giao hàng, kiểm hàng.
4. Tính ngưỡng tối thiểu ban đầu = tốc độ bán/ngày × thời gian nhập hàng.
5. Thêm vùng đệm theo nhóm ưu tiên và mùa vụ.
6. Làm tròn lên theo đơn vị đóng gói thực tế.
7. Nhập ngưỡng vào phần mềm quản lý kho hoặc file Excel có cảnh báo.
8. Phân công người kiểm tra cảnh báo vào giờ cố định.
9. Sau 4–8 tuần, rà soát số lần hết hàng và vốn tồn, chỉnh ngưỡng nếu cần.

Làm đúng quy trình này, mức tồn kho tối thiểu không còn là con số cảm tính. Nó trở thành công cụ giúp cửa hàng nhỏ giảm hết hàng bán chạy và tránh đọng vốn ở hàng chậm luân chuyển.
