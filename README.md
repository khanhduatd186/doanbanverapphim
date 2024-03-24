
I.Mô tả bài toán

Phần mềm vé xem phim CGV cho phép admin quản lý dữ liệu của rạp chiếu phim, khách hàng, tài khoản,nhân viên, hóa đơn, và dữ liệu bao gồm phim,lịch chiếu, thể loại phim, rạp, phòng chiếu, vé.
Mỗi tài khoản có một mã id, tên người dùng, mật khẩu và 1 id phân quyền. Mỗi quyền có 1 id , tên quyền (Khách hàng, Nhân Vien,Admin)

Một phần mềm bán vé xem phim CGV cho phép người dùng có thể xem lịch chiếu, rạp và quản lý vé xem phim của mình. Mỗi người dùng đăng ký một tài khoản CGV gồm id, họ tên, số diện thoại, tên người dùng và mật khẩu, ngoài ra thông tin người dùng còn có ngày sinh, địa chỉ.
Nếu đã có tài khoản, người dùng cần đăng nhập tài khoản bằng username và mật khẩu.
Phần mềm vé xem phim CGV cho phép admin quản lý dữ liệu của rạp chiếu phim, khách hàng, tài khoản,nhân viên, hóa đơn, và dữ liệu bao gồm phim,lịch chiếu, thể loại phim, rạp, phòng chiếu, vé.
Mỗi tài khoản có một mã id, tên người dùng, mật khẩu và 1 id phân quyền. Mỗi quyền có 1 id , tên quyền (Khách hàng, Nhân Vien,Admin).

Mỗi khách hàng lần đầu truy cập có thể đăng ký 1 tài khoản khách hàng gồm id, tên người dùng và mật khẩu, ngoài ra thông tin khách hàng còn có họ tên, ngày sinh, địa chỉ, số điện thoại và id khách hàng. Khách hàng có thể xem, tìm kiếm phim,chọn rạp, lịch chiếu, đặt vé và thanh toán tiền vé.
Mỗi nhân viên cũng được cấp 1 tài khoản nhân viên có mã id,tên người dùng và mật khẩu, họ tên, ngày sinh, địa chỉ và số điện thoại, và id quyền nhân viên có thể xác nhận và in vé cho khách hàng.
Mỗi vé xem phim sẽ được phân biệt với nhau bởi mã id, và bao gồm loại vé, idlichchieu, mã ghế ngồi, id khách hàng đặt vé, giá vé.
Mỗi lịch chiếu phim sẽ có mã id khác nhau, thời gian chiếu, id phòng chiếu và trạng thái phòng chiếu tỏng lịch chiếu đó (trống hay full chỗ)

Mỗi bộ phim được chiếu ở rạp được phân biệt với nhau bởi mã id, bao gồm tên phim, mô tả, thời lượng, ngày khởi chiếu, ngày kết thúc,nhà sản xuất, đạo diễn và năm sản xuất.
Ngày khởi chiếu phải bé hơn ngày kết thúc.

Ở rạp sẽ chiếu nhiều thể loại phim khác nhau, mỗi thể loại sẽ có mã id loại, tên thể loại và mô tả cho thể loại đó. Phim sẽ được phân loại dựa vào thể loại phim.

Rạp CGV có nhiều phòng chiếu khác nhau, mỗi phòng chiếu sẽ có id khác nhau, tên phòng chiếu, số chỗ ngồi, tình trạng ( trống hay đang chiếu phim).

Hệ thống Rạp chiếu phim có nhiều rạp ở những địa chỉ khác nhau, mỗi rạp có mã id để phân biệt, tên rạp và địa chỉ rạp, số lượng phòng chiếu.Admin có toàn quyền của phần mềm bán vé.

II. Mô tả
Cơ sở dữ liệu phần mềm bán vé xem phim  

https://github.com/khanhduatd186/doanbanverapphim/issues/1#issue-2204205493




 
Hình 1: Giao diện đăng nhập
Mô tả: Nếu đã có tài khỏa, thì nhập username và password, nếu đúng thì đăng nhập thành công.
Nếu chưa có tài khoản, nhấn đăng ký tài khoản CGV

         
Hình 2: Giao diện đăng ký
Nhập thông tin đăng ký gồm: Họ tên, tên tài khoản, mật khẩu, địa chỉ, số điện thoại và ngày sinh. Trong đó:
- Tên tài khoản dài từ 6-24 ký tự, chỉ nhập chữ và số ,chữ hoa
- Mật khẩu dài từ 6-24 ký tự, chỉ nhập chữ và số ,chữ hoa
- Xác nhận mật khẩu phải khớp với mật khẩu.

Hình 3: Giao diện quản lý của admin

Hình 4: Giao diện quản lý nhân viên của admin
- Admin có quyền quản lý nhân viên, khách hàng, doanh thu, tài khoản, và toàn bộ dữ liệu trong hệ thống.

Hình 5: Giao diện quản lý khách hàng
- Thông tin khách hàng đã đăng ký tài khoản.

Hình 5: Giao diện quản lý dữ liệu
- Thông tin phòng chiếu 


Hình 6: Giao diện quản lý vé
- Vé có thể tạo tự động thông qua lịch chiếu và phim

Hình 7: Giao diện quản lý phim

Hình 8: Giao diện quản lý doanh thu
- Admin quản lý doanh thu của rạp theo từng phim và từng khoảng thời gian.

Hình 9 :Giao diện quản lý tài khoản



Hình 9: Giao diện xem lịch chiếu phim của khách hàng

Hình 10: Giao diện quản lý vé của khách hàng
- Tài khoản khách hàng có quyền xem vé mình đã đặt.s






