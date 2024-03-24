
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


![admin](https://github.com/khanhduatd186/doanbanverapphim/assets/127516595/24eb3ebf-93e0-4b53-aa25-dbcba9aee331)


 
Hình 1: Giao diện đăng nhập
Mô tả: Nếu đã có tài khỏa, thì nhập username và password, nếu đúng thì đăng nhập thành công.
Nếu chưa có tài khoản, nhấn đăng ký tài khoản CGV

 ![dangky](https://github.com/khanhduatd186/doanbanverapphim/assets/127516595/51a0e731-9981-43ed-81ce-698aa2001298)

Hình 2: Giao diện đăng ký


Nhập thông tin đăng ký gồm: Họ tên, tên tài khoản, mật khẩu, địa chỉ, số điện thoại và ngày sinh. Trong đó:
- Tên tài khoản dài từ 6-24 ký tự, chỉ nhập chữ và số ,chữ hoa
- Mật khẩu dài từ 6-24 ký tự, chỉ nhập chữ và số ,chữ hoa
- Xác nhận mật khẩu phải khớp với mật khẩu.
![quanlyadmin](https://github.com/khanhduatd186/doanbanverapphim/assets/127516595/6a642000-ad6f-4319-917a-187b0eda6b83)

Hình 3: Giao diện quản lý của admin
![quanlynhanvien](https://github.com/khanhduatd186/doanbanverapphim/assets/127516595/84428f96-b372-4806-a2b4-4bf413b4cb9d)

Hình 4: Giao diện quản lý nhân viên của admin
- Admin có quyền quản lý nhân viên, khách hàng, doanh thu, tài khoản, và toàn bộ dữ liệu trong hệ thống.
![giaodienkhachhang](https://github.com/khanhduatd186/doanbanverapphim/assets/127516595/1b4e167d-282c-43a1-ad40-dc23f9f2ee51)

Hình 5: Giao diện quản lý khách hàng
- Thông tin khách hàng đã đăng ký tài khoản.
![quanlydulieu](https://github.com/khanhduatd186/doanbanverapphim/assets/127516595/51417df0-65be-4b34-88f4-735718222774)

Hình 5: Giao diện quản lý dữ liệu
- Thông tin phòng chiếu 
![quanlyve](https://github.com/khanhduatd186/doanbanverapphim/assets/127516595/ea908f29-1140-4042-9d2d-b83caeecfb46)

Hình 6: Giao diện quản lý vé
- Vé có thể tạo tự động thông qua lịch chiếu và phim
![quanlyphim](https://github.com/khanhduatd186/doanbanverapphim/assets/127516595/891c5a61-3c41-4e06-b986-a90d44ea97ef)

Hình 7: Giao diện quản lý phim
![quanlydoanhthu](https://github.com/khanhduatd186/doanbanverapphim/assets/127516595/9145a59b-f1b3-4d05-9ef7-beee8642c298)

Hình 8: Giao diện quản lý doanh thu
- Admin quản lý doanh thu của rạp theo từng phim và từng khoảng thời gian.
![quanlytaikhoan](https://github.com/khanhduatd186/doanbanverapphim/assets/127516595/9a64f696-2e36-48bd-a2b6-31c7b985d326)
Hình 9 :Giao diện quản lý tài khoản


![phim](https://github.com/khanhduatd186/doanbanverapphim/assets/127516595/2611fbd1-ce6e-4d8a-a1fe-52883701b231)
Hình 9: Giao diện xem lịch chiếu phim của khách hàng
![ve dat dac](https://github.com/khanhduatd186/doanbanverapphim/assets/127516595/05ed7e90-de4b-4166-9f48-bba19fc1ab99)
Hình 10: Giao diện quản lý vé của khách hàng
- Tài khoản khách hàng có quyền xem vé mình đã đặt.s
![api](https://github.com/khanhduatd186/doanbanverapphim/assets/127516595/ff225ced-d361-48ba-9969-4f15c2461d72)
![ghe](https://github.com/khanhduatd186/doanbanverapphim/assets/127516595/e23b95d5-ce2d-482a-a83d-9f49a383dd2a)
![phim](https://github.com/khanhduatd186/doanbanverapphim/assets/127516595/2611fbd1-ce6e-4d8a-a1fe-52883701b231)





