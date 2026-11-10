# Playlist IPTV chọn lọc cho LaunchPad TV

163 kênh riêng biệt, chia 15 danh mục. File có 179 mục vì một số kênh thể thao xuất hiện trong nhiều nhóm theo giải đấu.

## Link để thêm vào TV

**Playlist M3U:**

```text
https://raw.githubusercontent.com/phanan04/playlist-iptv/main/playlist.m3u
```

[Mở playlist](https://raw.githubusercontent.com/phanan04/playlist-iptv/main/playlist.m3u) · [Danh sách kênh](DANH-SACH-KENH.md)

Với LaunchPad TV, có thể đăng ký link này thành code loại IPTV tại https://tv.launchpad2.app rồi nhập code trên TV.

## Danh mục

1. Việt Nam — tổng hợp
2. Tin tức quốc tế
4. Thiếu nhi và hoạt hình
6. Khoa học và khám phá
10. F1
11. C1 — kênh theo lịch
12. Ngoại hạng Anh — kênh theo lịch
13. La Liga — kênh theo lịch
14. Bóng đá tổng hợp
15. Bóng chuyền
16. Tennis
18. Võ thuật và quyền Anh
19. Golf
20. Đua xe và thể thao mạo hiểm
22. Thể thao tổng hợp

## Nguồn và phạm vi kiểm tra

- Chọn lọc ngày **10/11/2026** từ [IPTV-org](https://github.com/iptv-org/iptv): [toàn bộ kênh](https://iptv-org.github.io/iptv/index.m3u), [thể thao](https://iptv-org.github.io/iptv/categories/sports.m3u).
- VTV1–VTV10 dùng nguồn M3U8 đã kiểm tra có nhánh 1920×1080 và trả dữ liệu video. Các kênh khác giữ URL phát và thông tin từ danh sách gốc.
- VTV6 dùng luồng HLS từ [playlist vmttv](https://d.org.vn/listiptv), đã kiểm tra có nhánh 1920×1080 và tải được một đoạn video.
- Lịch VTV1–VTV10 lấy từ [VNEPG (XMLTV)](https://epg.io.vn/epg.xml). Playlist gắn URL lịch và mã kênh tương ứng. Khả năng hiện lịch khi nhập bằng mã IPTV tùy trình nhập của LaunchPad.
- Đây là lựa chọn theo nhu cầu xem, không phải bảng xếp hạng lượng người xem.
- Chưa xác minh phát từng luồng trên TV tại Việt Nam. Một số luồng có thể hết hạn, giới hạn vùng hoặc ngừng hoạt động. Kênh nước ngoài không mặc nhiên có tiếng Việt hay phụ đề Việt.
- Nhóm theo giải chỉ là đường truy cập nhanh tới các kênh liên quan; phải xem lịch phát và phiên bản kênh theo quốc gia, không bảo đảm có mọi trận.
- Trình phát có thể tự gộp các mục có cùng URL, khi đó một kênh có thể chỉ xuất hiện trong nhóm đầu tiên.
- Playlist là bản chụp tại thời điểm lọc, chưa có lịch tự động cập nhật. Repository không lưu trữ video.
