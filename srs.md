# B1. Xác định Business Context và Business Problem

## 1. Business Context – Bối cảnh nghiệp vụ

Công ty ABC đang cung cấp dịch vụ đặt xe trực tuyến thông qua tổng đài và một ứng dụng đơn giản. Tuy nhiên, doanh nghiệp đang có nhu cầu xây dựng **CAB System** mới để tự động hóa và quản lý tập trung toàn bộ quy trình đặt xe, từ khi khách hàng yêu cầu xe, tìm và phân công tài xế, thực hiện chuyến, thanh toán đến đánh giá sau chuyến.

**Đối tượng sử dụng chính:**
- Khách hàng
- Tài xế
- Nhân viên vận hành

Hệ thống cũng cần tích hợp với **cổng thanh toán điện tử và dịch vụ thông báo** bên ngoài.

## 2. Business Problem – Vấn đề nghiệp vụ

Hệ thống hiện tại tồn tại các vấn đề:

- Phân công tài xế còn **thủ công**, mất thời gian và khó tối ưu.
- Khách hàng **khó theo dõi trạng thái chuyến đi**.
- Thanh toán và giao dịch **chưa được quản lý tập trung**.
- Nhân viên vận hành gặp khó khăn trong việc **quản lý khách hàng, tài xế, chuyến đi và xử lý sự cố**.
- Khó tổng hợp dữ liệu để theo dõi **doanh thu, số chuyến, tỷ lệ hoàn thành và tỷ lệ hủy**.
- Hệ thống **khó mở rộng** khi số lượng khách hàng và tài xế tăng.

## 3. Mục tiêu kinh doanh

- Tự động hóa quy trình đặt xe và phân công tài xế.
- Nâng cao trải nghiệm và khả năng theo dõi chuyến của khách hàng.
- Quản lý tập trung chuyến đi, thanh toán và dữ liệu vận hành.
- Giảm thao tác thủ công và nâng cao hiệu quả của nhân viên.
- Xây dựng hệ thống **ổn định, bảo mật và có khả năng mở rộng**.

## 4. Giá trị của hệ thống mới

So với hệ thống cũ, CAB System giúp **tự động hóa việc tìm tài xế, theo dõi chuyến, thanh toán và thông báo**, đồng thời cung cấp dữ liệu phục vụ quản lý và báo cáo.

Hệ thống giúp **giảm thời gian xử lý, nâng cao chất lượng dịch vụ, tăng hiệu quả vận hành và tạo nền tảng để doanh nghiệp mở rộng trong tương lai**.

# B2. Xác định các bên liên quan (Stakeholders)
1.	Những stalkholder - 	Vai trò là gì 
2.	Vẽ ma trận stalkholder matrick
## 1. Những stalkholder - 	Vai trò là gì 

| Stakeholder | Vai trò |
|---|---|
| Khách hàng | Đăng ký, đặt xe, theo dõi chuyến, thanh toán và đánh giá tài xế. |
| Tài xế | Nhận chuyến, chấp nhận/từ chối chuyến, thực hiện chuyến và cập nhật trạng thái. |
| Nhân viên vận hành | Quản lý khách hàng, tài xế, phương tiện, chuyến đi và xử lý sự cố. |
| Ban giám đốc | Xác định mục tiêu kinh doanh, theo dõi doanh thu và hiệu quả hoạt động. |
| Bộ phận kế toán/tài chính | Theo dõi giao dịch, thanh toán và doanh thu. |
| Nhà cung cấp thanh toán | Xử lý các giao dịch thanh toán điện tử. |
| Nhà cung cấp thông báo | Cung cấp dịch vụ gửi thông báo như SMS, Email hoặc các kênh khác. |
| Business Analyst (BA) | Thu thập, phân tích và làm rõ yêu cầu của các bên liên quan. |
| Đội phát triển hệ thống | Thiết kế, xây dựng, kiểm thử và triển khai hệ thống. |
| Tài xế | Nhận chuyến, chấp nhận/từ chối chuyến, thực hiện chuyến và cập nhật trạng thái. |
| Nhân viên vận hành | Quản lý khách hàng, tài xế, phương tiện, chuyến đi và xử lý sự cố. |
| Ban giám đốc | Xác định mục tiêu kinh doanh, theo dõi doanh thu và hiệu quả hoạt động. |
| Bộ phận kế toán/tài chính | Theo dõi giao dịch, thanh toán và doanh thu. |
| Nhà cung cấp thanh toán | Xử lý các giao dịch thanh toán điện tử. |
| Nhà cung cấp thông báo | Cung cấp dịch vụ gửi thông báo như SMS, Email hoặc các kênh khác. |
| Business Analyst (BA) | Thu thập, phân tích và làm rõ yêu cầu của các bên liên quan. |
| Đội phát triển hệ thống | Thiết kế, xây dựng, kiểm thử và triển khai hệ thống. |

2.	Vẽ ma trận stalkholder matrick
## 3. Stakeholder Matrix

Ma trận Stakeholder được phân tích dựa trên hai tiêu chí:

- **Mức độ ảnh hưởng (Power):** Khả năng tác động đến quyết định, phạm vi, tiến độ và kết quả dự án.
- **Mức độ quan tâm (Interest):** Mức độ quan tâm của stakeholder đối với kết quả và hoạt động của hệ thống.

| MỨC ĐỘ ẢNH HƯỞNG | MỨC ĐỘ QUAN TÂM THẤP | MỨC ĐỘ QUAN TÂM CAO |
|---|---|---|
| **CAO** | Bộ phận tài chính<br>Nhà cung cấp thanh toán<br>Nhà cung cấp thông báo | Ban lãnh đạo<br>Nhân viên vận hành<br>System Admin<br>Business Analyst |
| **THẤP** | Stakeholder gián tiếp | Khách hàng<br>Tài xế<br>Đội phát triển<br>QA/Test |

### Sơ đồ Stakeholder Matrix

```text
                    MỨC ĐỘ ẢNH HƯỞNG (POWER)
                              CAO
                               │
                               │
          KEEP SATISFIED      │        MANAGE CLOSELY
                               │
          Bộ phận tài chính   │        Ban lãnh đạo
          Payment Provider    │        Nhân viên vận hành
          Notification        │        System Admin
          Provider            │        Business Analyst
                               │
───────────────────────────────┼──────────────────────────────
                               │
          MONITOR              │        KEEP INFORMED
                               │
          Stakeholder          │        Khách hàng
          gián tiếp            │        Tài xế
                               │        Đội phát triển
                               │        QA / Test
                               │
                               │
                              THẤP
                    MỨC ĐỘ QUAN TÂM (INTEREST)
                         THẤP       →       CAO
```
# B3. Xác định Business Goals

## BG01. Tự động hóa quy trình đặt xe

- Hệ thống tự động tiếp nhận và xử lý yêu cầu đặt xe.
- Giảm thao tác thủ công của nhân viên vận hành.
- Đảm bảo quy trình từ đặt xe đến hoàn thành chuyến được xử lý xuyên suốt.

## BG02. Tự động tìm và phân công tài xế

- Hệ thống tự động tìm tài xế phù hợp.
- Ưu tiên tài xế gần khách hàng và đang sẵn sàng.
- Tự động tìm tài xế khác khi tài xế từ chối hoặc không phản hồi.
- Thông báo cho khách hàng khi tìm được hoặc không tìm được tài xế.

## BG03. Nâng cao trải nghiệm khách hàng

- Cho phép khách hàng đặt xe nhanh chóng.
- Cho phép khách hàng theo dõi trạng thái chuyến.
- Cung cấp thông tin tài xế và thời gian dự kiến đến.
- Cho phép khách hàng xem lịch sử chuyến và đánh giá tài xế.

## BG04. Nâng cao hiệu quả vận hành

- Cho phép nhân viên quản lý khách hàng, tài xế, phương tiện và chuyến đi.
- Cho phép theo dõi các chuyến đang diễn ra.
- Hỗ trợ xử lý các trường hợp chuyến bị lỗi.
- Hỗ trợ tra cứu lịch sử giao dịch.

## BG05. Quản lý tính cước và thanh toán

- Tự động xác định số tiền khách hàng phải thanh toán.
- Hỗ trợ thanh toán tiền mặt.
- Hỗ trợ thanh toán điện tử thông qua Payment Provider.
- Xử lý trường hợp thanh toán thất bại.
- Không lưu trực tiếp thông tin thanh toán nhạy cảm.

## BG06. Xây dựng hệ thống thông báo

- Thông báo cho khách hàng về các sự kiện quan trọng của chuyến.
- Thông báo cho tài xế khi có chuyến mới hoặc thay đổi chuyến.
- Cho phép mở rộng thêm các kênh thông báo trong tương lai.

## BG07. Quản lý và khai thác dữ liệu

- Lưu trữ lịch sử chuyến đi.
- Lưu trữ lịch sử giao dịch.
- Lưu trữ dữ liệu vị trí tài xế.
- Lưu vết các thao tác quan trọng.
- Hỗ trợ tra cứu và kiểm tra dữ liệu khi xảy ra sự cố.

## BG08. Hỗ trợ báo cáo và quản lý hiệu quả

- Theo dõi số lượng chuyến.
- Theo dõi doanh thu.
- Theo dõi tỷ lệ chuyến hoàn thành.
- Theo dõi tỷ lệ chuyến hủy.
- Theo dõi hiệu quả hoạt động của tài xế.

## BG09. Đảm bảo bảo mật và phân quyền

- Xác thực khách hàng, tài xế và nhân viên.
- Phân quyền chức năng quản trị.
- Bảo vệ thông tin cá nhân.
- Bảo vệ dữ liệu phương tiện, vị trí và giao dịch.
- Lưu audit log đối với các thao tác quan trọng.

## BG10. Đảm bảo tính ổn định và khả năng mở rộng

- Hệ thống hoạt động ổn định khi nhu cầu tăng cao.
- Các thành phần có khả năng mở rộng độc lập.
- Lỗi ở Payment hoặc Notification không làm toàn bộ hệ thống đặt xe ngừng hoạt động.
- Cho phép triển khai từng phần mà hạn chế ảnh hưởng đến chức năng đang hoạt động.

## BG11. Hỗ trợ phát triển hệ thống trong tương lai

- Cho phép bổ sung loại dịch vụ mới.
- Cho phép bổ sung phương thức thanh toán mới.
- Cho phép tích hợp thêm Payment Provider.
- Cho phép tích hợp thêm Notification Provider.
- Cho phép thay đổi thành phần kỹ thuật mà không phải xây dựng lại toàn bộ hệ thống.

## BG12. Hoàn thành MVP trong 7 tuần

- Xác định và ưu tiên các chức năng cốt lõi.
- Hoàn thành phiên bản MVP trong thời gian 7 tuần.
- Ưu tiên quy trình:

```text
Đặt xe
  ↓
Tìm tài xế
  ↓
Phân công tài xế
  ↓
Thực hiện chuyến
  ↓
Hoàn thành chuyến
  ↓
Tính cước
  ↓
Thanh toán
  ↓
Thông báo
  ↓
Đánh giá
```
## B4: Xác định PHẠM VI SCOPE: 
1. Quản lý tài khoản người dùng
- Đăng ký và đăng nhập tài khoản khách hàng.
- Quản lý thông tin cá nhân khách hàng.
- Quản lý tài khoản và hồ sơ tài xế.
- Quản lý quyền truy cập của nhân viên vận hành và quản trị viên.
2. Quản lý tài xế và phương tiện
- Quản lý thông tin tài xế.
- Quản lý thông tin phương tiện.
- Theo dõi trạng thái hoạt động của tài xế.
- Theo dõi vị trí của tài xế.
- Quản lý khả năng nhận chuyến của tài xế.
3. Đặt xe và phân công tài xế
- Nhập điểm đón và điểm đến.
- Lựa chọn loại xe.
- Tiếp nhận yêu cầu đặt xe.
- Tìm kiếm tài xế phù hợp.
- Ưu tiên tài xế dựa trên vị trí, trạng thái và tiêu chí vận hành.
- Tiếp tục tìm tài xế khác khi tài xế từ chối hoặc không phản hồi.
- Thông báo khi không tìm được tài xế.
4. Quản lý chuyến đi
- Theo dõi trạng thái chuyến đi.
- Cập nhật trạng thái chuyến.
- Theo dõi thời gian dự kiến tài xế đến.
- Quản lý quá trình thực hiện chuyến.
- Xử lý các trường hợp chuyến bị hủy hoặc gặp sự cố.
- Lưu lịch sử chuyến đi.
5. Tính cước và thanh toán
- Xác định số tiền khách hàng phải trả.
- Hỗ trợ thanh toán bằng tiền mặt.
- Hỗ trợ thanh toán điện tử/chuyển khoản.
- Tích hợp với nhà cung cấp thanh toán bên ngoài.
- Xử lý kết quả thanh toán.
- Xử lý trường hợp thanh toán thất bại.
- Lưu lịch sử giao dịch.
- Không lưu trực tiếp thông tin nhạy cảm của thẻ hoặc tài khoản thanh toán.
6. Thông báo
- Thông báo cho khách hàng về trạng thái đặt xe.
- Thông báo khi tài xế nhận chuyến.
- Thông báo khi tài xế đến điểm đón.
- Thông báo khi chuyến hoàn thành.
- Thông báo kết quả thanh toán.
- Thông báo cho tài xế về chuyến mới và các thay đổi liên quan đến chuyến đi.
- Hỗ trợ mở rộng thêm các kênh thông báo trong tương lai.
7. Đánh giá và phản hồi
- Khách hàng đánh giá tài xế sau khi hoàn thành chuyến.
- Lưu thông tin đánh giá.
- Theo dõi chất lượng phục vụ của tài xế.
8. Quản trị và vận hành
- Quản lý khách hàng.
- Quản lý tài xế.
- Quản lý phương tiện.
- Theo dõi các chuyến đang diễn ra.
- Kiểm tra trạng thái tài xế.
- Hỗ trợ xử lý các chuyến bị lỗi.
- Tra cứu lịch sử giao dịch.
- Phân quyền các thao tác quản trị.
9. Báo cáo
- Báo cáo số lượng chuyến.
- Báo cáo doanh thu.
- Báo cáo tỷ lệ chuyến hoàn thành.
- Báo cáo tỷ lệ hủy chuyến.
- Báo cáo hiệu quả hoạt động của tài xế.
10. Bảo mật và kiểm soát
- Xác thực người dùng.
- Phân quyền truy cập.
- Bảo vệ thông tin cá nhân.
- Bảo vệ dữ liệu phương tiện.
- - Bảo vệ dữ liệu vị trí.
- Bảo vệ dữ liệu giao dịch.
- Lưu vết các thao tác quan trọng.
### 11. Những chức năng KHÔNG nên làm trong MVP

> Các chức năng dưới đây **không nằm trong phạm vi MVP 7 tuần**, có thể xem xét ở các phiên bản tiếp theo.

#### 11.1. Quản lý tài khoản nâng cao
- Đăng nhập bằng Google/Facebook/Apple.
- Đăng nhập đa yếu tố (MFA) nâng cao.
- Single Sign-On (SSO).
- Quản lý nhiều thiết bị đăng nhập.
- Hệ thống thành viên nhiều cấp.
- Chương trình khách hàng thân thiết (Loyalty).

#### 11.2. Đặt xe nâng cao
- Đặt xe theo lịch trong tương lai.
- Đặt xe khứ hồi.
- Đặt xe nhiều điểm dừng.
- Đặt xe cho nhiều hành khách.
- Chia sẻ chuyến xe (Ride Sharing).
- Đặt xe theo nhóm.
- Đặt xe doanh nghiệp (Corporate Booking).

#### 11.3. Tìm và phân công tài xế nâng cao
- Sử dụng AI/Machine Learning để phân công tài xế.
- Dự đoán nhu cầu xe theo khu vực.
- Tối ưu phân công nhiều chuyến cùng lúc.
- Dynamic Dispatch nâng cao.
- Tự động điều chỉnh thuật toán dựa trên dữ liệu lịch sử.
- Hệ thống dự đoán thời gian đến bằng AI.

#### 11.4. Tính cước nâng cao
- Dynamic Pricing phức tạp.
- Surge Pricing.
- Hệ thống khuyến mãi nâng cao.
- Hệ thống voucher/coupon phức tạp.
- Loyalty Discount.
- Tự động tối ưu giá bằng AI.
- Nhiều mô hình tính cước phức tạp chưa được khách hàng xác nhận.

#### 11.5. Thanh toán nâng cao
- Tích hợp nhiều nhà cung cấp thanh toán cùng lúc.
- Xây dựng ví điện tử riêng.
- Thanh toán định kỳ (Subscription).
- Auto Billing.
- Hệ thống chia nhỏ và phân bổ thanh toán phức tạp.
- Hệ thống đối soát tài chính tự động nâng cao.

#### 11.6. Thông báo nâng cao
- Triển khai đồng thời quá nhiều kênh thông báo.
- Hệ thống gửi thông báo Marketing.
- Campaign Notification.
- Notification Analytics nâng cao.
- Hệ thống tự động tối ưu nội dung thông báo.
- Chatbot thông báo.

#### 11.7. Tính năng dành cho tài xế nâng cao
- Hệ thống thưởng/phạt tự động.
- Hệ thống hoa hồng phức tạp.
- Driver Ranking nâng cao.
- Gamification cho tài xế.
- Chương trình thưởng theo hiệu suất.
- Phân tích hành vi lái xe bằng AI.
- Hệ thống đào tạo tài xế trực tuyến.

#### 11.8. Bản đồ và điều hướng nâng cao
- Xây dựng hệ thống bản đồ riêng.
- Xây dựng hệ thống Navigation riêng.
- Tối ưu tuyến đường bằng AI.
- Phân tích giao thông nâng cao.
- Heatmap giao thông.
- Dự đoán tình trạng giao thông.
- Tự phát triển thuật toán bản đồ thay cho Map Provider.

#### 11.9. Báo cáo và phân tích nâng cao
- Business Intelligence Platform.
- - Data Warehouse phức tạp.
- Predictive Analytics.
- Forecasting doanh thu bằng AI.
- Dashboard phân tích realtime nâng cao.
- Custom Report Builder.
- Phân tích hành vi khách hàng nâng cao.

#### 11.10. Chăm sóc khách hàng nâng cao
- Chat trực tiếp giữa khách hàng và tài xế.
- Chatbot AI.
- Trung tâm hỗ trợ khách hàng đa kênh.
- Hệ thống Ticketing nâng cao.
- Tổng đài VoIP tích hợp.
- CRM Platform đầy đủ.

#### 11.11. Mở rộng dịch vụ
- Giao hàng.
- Gọi xe đường dài.
- Thuê xe theo giờ.
- Xe hợp đồng.
- Vận chuyển hàng hóa.
- Các loại dịch vụ khác chưa được xác định trong phạm vi MVP.

#### 11.12. Quản trị nâng cao
- Workflow phê duyệt nhiều cấp.
- Custom Role Builder.
- Custom Permission Builder phức tạp.
- Audit Dashboard nâng cao.
- Tự động hóa toàn bộ quy trình vận hành.
- Hệ thống quản trị nhiều công ty/chi nhánh.

---

### 12. Các vấn đề CHƯA ĐỦ THÔNG TIN – Không tự triển khai

Các nội dung dưới đây cần được **Business Analyst xác nhận với khách hàng** trước khi đưa vào Development:

- Công thức tính cước cụ thể.
- Tiêu chí ưu tiên tài xế.
- Khoảng cách tối đa để tìm tài xế.
- Thời gian tài xế phải phản hồi yêu cầu.
- Số lần hệ thống thử tìm tài xế.
- Chính sách khi tài xế từ chối chuyến.
- Chính sách khi tài xế không phản hồi.
- Chính sách hủy chuyến của khách hàng.
- Chính sách hủy chuyến của tài xế.
- Phí hủy chuyến.
- Chính sách xử lý thanh toán thất bại.
- Quy định khi khách hàng mất kết nối mạng.
- Quy định khi tài xế mất kết nối mạng.
- Tần suất cập nhật vị trí tài xế.
- Thời gian lưu trữ dữ liệu.
- Chính sách đánh giá tài xế.
- Quy định xử lý đánh giá không hợp lệ.
- Chi tiết phân quyền nhân viên vận hành.
- Quy định về dữ liệu cá nhân và thời gian lưu trữ dữ liệu.

---

### 13. Nguyên tắc Scope cho MVP

```text
                     CAB SYSTEM MVP
                           │
          ┌────────────────┼────────────────┐
          │                │                │
          ▼                ▼                ▼
     PHẢI LÀM          CÓ THỂ LÀM        KHÔNG LÀM
      (MVP)            SAU MVP            (MVP)
          │                │                │
          ▼                ▼                ▼
     Đặt xe           Loyalty           AI Dispatch
     Tìm tài xế      Voucher            Dynamic Pricing
     Chuyến đi       Scheduled Ride     Chatbot AI
     Tính cước       Corporate Ride     Ride Sharing
     Thanh toán      Nhiều Payment      Ví điện tử
Thông báo       Nhiều Channel      BI nâng cao
     Đánh giá        Dịch vụ mới        Navigation riêng
     Admin           Báo cáo nâng cao    CRM đầy đủ
```
## B4: Xác định PHẠM VI SCOPE: 
1. Quản lý tài khoản người dùng
- Đăng ký và đăng nhập tài khoản khách hàng.
- Quản lý thông tin cá nhân khách hàng.
- Quản lý tài khoản và hồ sơ tài xế.
- Quản lý quyền truy cập của nhân viên vận hành và quản trị viên.
2. Quản lý tài xế và phương tiện
- Quản lý thông tin tài xế.
- Quản lý thông tin phương tiện.
- Theo dõi trạng thái hoạt động của tài xế.
- Theo dõi vị trí của tài xế.
- Quản lý khả năng nhận chuyến của tài xế.
3. Đặt xe và phân công tài xế
- Nhập điểm đón và điểm đến.
- Lựa chọn loại xe.
- Tiếp nhận yêu cầu đặt xe.
- Tìm kiếm tài xế phù hợp.
- Ưu tiên tài xế dựa trên vị trí, trạng thái và tiêu chí vận hành.
- Tiếp tục tìm tài xế khác khi tài xế từ chối hoặc không phản hồi.
- Thông báo khi không tìm được tài xế.
4. Quản lý chuyến đi
- Theo dõi trạng thái chuyến đi.
- Cập nhật trạng thái chuyến.
- Theo dõi thời gian dự kiến tài xế đến.
- Quản lý quá trình thực hiện chuyến.
- Xử lý các trường hợp chuyến bị hủy hoặc gặp sự cố.
- Lưu lịch sử chuyến đi.
5. Tính cước và thanh toán
- Xác định số tiền khách hàng phải trả.
- Hỗ trợ thanh toán bằng tiền mặt.
- Hỗ trợ thanh toán điện tử/chuyển khoản.
- Tích hợp với nhà cung cấp thanh toán bên ngoài.
- Xử lý kết quả thanh toán.
- Xử lý trường hợp thanh toán thất bại.
- Lưu lịch sử giao dịch.
- Không lưu trực tiếp thông tin nhạy cảm của thẻ hoặc tài khoản thanh toán.
6. Thông báo
- Thông báo cho khách hàng về trạng thái đặt xe.
- Thông báo khi tài xế nhận chuyến.
- Thông báo khi tài xế đến điểm đón.
- Thông báo khi chuyến hoàn thành.
- Thông báo kết quả thanh toán.
- Thông báo cho tài xế về chuyến mới và các thay đổi liên quan đến chuyến đi.
- Hỗ trợ mở rộng thêm các kênh thông báo trong tương lai.
7. Đánh giá và phản hồi
- Khách hàng đánh giá tài xế sau khi hoàn thành chuyến.
- Lưu thông tin đánh giá.
- Theo dõi chất lượng phục vụ của tài xế.
8. Quản trị và vận hành
- Quản lý khách hàng.
- Quản lý tài xế.
- Quản lý phương tiện.
- Theo dõi các chuyến đang diễn ra.
- Kiểm tra trạng thái tài xế.
- Hỗ trợ xử lý các chuyến bị lỗi.
- Tra cứu lịch sử giao dịch.
- Phân quyền các thao tác quản trị.
9. Báo cáo
- Báo cáo số lượng chuyến.
- Báo cáo doanh thu.
- Báo cáo tỷ lệ chuyến hoàn thành.
- Báo cáo tỷ lệ hủy chuyến.
- Báo cáo hiệu quả hoạt động của tài xế.
10. Bảo mật và kiểm soát
- Xác thực người dùng.
- Phân quyền truy cập.
- - Bảo vệ thông tin cá nhân.
- Bảo vệ dữ liệu phương tiện.
- Bảo vệ dữ liệu vị trí.
- Bảo vệ dữ liệu giao dịch.
- Lưu vết các thao tác quan trọng.
### 11. Những chức năng KHÔNG nên làm trong MVP

> Các chức năng dưới đây **không nằm trong phạm vi MVP 7 tuần**, có thể xem xét ở các phiên bản tiếp theo.

#### 11.1. Quản lý tài khoản nâng cao
- Đăng nhập bằng Google/Facebook/Apple.
- Đăng nhập đa yếu tố (MFA) nâng cao.
- Single Sign-On (SSO).
- Quản lý nhiều thiết bị đăng nhập.
- Hệ thống thành viên nhiều cấp.
- Chương trình khách hàng thân thiết (Loyalty).

#### 11.2. Đặt xe nâng cao
- Đặt xe theo lịch trong tương lai.
- Đặt xe khứ hồi.
- Đặt xe nhiều điểm dừng.
- Đặt xe cho nhiều hành khách.
- Chia sẻ chuyến xe (Ride Sharing).
- Đặt xe theo nhóm.
- Đặt xe doanh nghiệp (Corporate Booking).

#### 11.3. Tìm và phân công tài xế nâng cao
- Sử dụng AI/Machine Learning để phân công tài xế.
- Dự đoán nhu cầu xe theo khu vực.
- Tối ưu phân công nhiều chuyến cùng lúc.
- Dynamic Dispatch nâng cao.
- Tự động điều chỉnh thuật toán dựa trên dữ liệu lịch sử.
- Hệ thống dự đoán thời gian đến bằng AI.

#### 11.4. Tính cước nâng cao
- Dynamic Pricing phức tạp.
- Surge Pricing.
- Hệ thống khuyến mãi nâng cao.
- Hệ thống voucher/coupon phức tạp.
- Loyalty Discount.
- Tự động tối ưu giá bằng AI.
- Nhiều mô hình tính cước phức tạp chưa được khách hàng xác nhận.

#### 11.5. Thanh toán nâng cao
- Tích hợp nhiều nhà cung cấp thanh toán cùng lúc.
- Xây dựng ví điện tử riêng.
- Thanh toán định kỳ (Subscription).
- Auto Billing.
- Hệ thống chia nhỏ và phân bổ thanh toán phức tạp.
- Hệ thống đối soát tài chính tự động nâng cao.

#### 11.6. Thông báo nâng cao
- Triển khai đồng thời quá nhiều kênh thông báo.
- Hệ thống gửi thông báo Marketing.
- Campaign Notification.
- Notification Analytics nâng cao.
- Hệ thống tự động tối ưu nội dung thông báo.
- Chatbot thông báo.

#### 11.7. Tính năng dành cho tài xế nâng cao
- Hệ thống thưởng/phạt tự động.
- Hệ thống hoa hồng phức tạp.
- Driver Ranking nâng cao.
- Gamification cho tài xế.
- Chương trình thưởng theo hiệu suất.
- Phân tích hành vi lái xe bằng AI.
- Hệ thống đào tạo tài xế trực tuyến.

#### 11.8. Bản đồ và điều hướng nâng cao
- Xây dựng hệ thống bản đồ riêng.
- Xây dựng hệ thống Navigation riêng.
- Tối ưu tuyến đường bằng AI.
- Phân tích giao thông nâng cao.
- Heatmap giao thông.
- Dự đoán tình trạng giao thông.
- - Tự phát triển thuật toán bản đồ thay cho Map Provider.

#### 11.9. Báo cáo và phân tích nâng cao
- Business Intelligence Platform.
- Data Warehouse phức tạp.
- Predictive Analytics.
- Forecasting doanh thu bằng AI.
- Dashboard phân tích realtime nâng cao.
- Custom Report Builder.
- Phân tích hành vi khách hàng nâng cao.

#### 11.10. Chăm sóc khách hàng nâng cao
- Chat trực tiếp giữa khách hàng và tài xế.
- Chatbot AI.
- Trung tâm hỗ trợ khách hàng đa kênh.
- Hệ thống Ticketing nâng cao.
- Tổng đài VoIP tích hợp.
- CRM Platform đầy đủ.

#### 11.11. Mở rộng dịch vụ
- Giao hàng.
- Gọi xe đường dài.
- Thuê xe theo giờ.
- Xe hợp đồng.
- Vận chuyển hàng hóa.
- Các loại dịch vụ khác chưa được xác định trong phạm vi MVP.

#### 11.12. Quản trị nâng cao
- Workflow phê duyệt nhiều cấp.
- Custom Role Builder.
- Custom Permission Builder phức tạp.
- Audit Dashboard nâng cao.
- Tự động hóa toàn bộ quy trình vận hành.
- Hệ thống quản trị nhiều công ty/chi nhánh.

---

### 12. Các vấn đề CHƯA ĐỦ THÔNG TIN – Không tự triển khai

Các nội dung dưới đây cần được **Business Analyst xác nhận với khách hàng** trước khi đưa vào Development:

- Công thức tính cước cụ thể.
- Tiêu chí ưu tiên tài xế.
- Khoảng cách tối đa để tìm tài xế.
- Thời gian tài xế phải phản hồi yêu cầu.
- Số lần hệ thống thử tìm tài xế.
- Chính sách khi tài xế từ chối chuyến.
- Chính sách khi tài xế không phản hồi.
- Chính sách hủy chuyến của khách hàng.
- Chính sách hủy chuyến của tài xế.
- Phí hủy chuyến.
- Chính sách xử lý thanh toán thất bại.
- Quy định khi khách hàng mất kết nối mạng.
- Quy định khi tài xế mất kết nối mạng.
- Tần suất cập nhật vị trí tài xế.
- Thời gian lưu trữ dữ liệu.
- Chính sách đánh giá tài xế.
- Quy định xử lý đánh giá không hợp lệ.
- Chi tiết phân quyền nhân viên vận hành.
- Quy định về dữ liệu cá nhân và thời gian lưu trữ dữ liệu.

---

### 13. Nguyên tắc Scope cho MVP

```text
                     CAB SYSTEM MVP
                           │
          ┌────────────────┼────────────────┐
          │                │                │
          ▼                ▼                ▼
     PHẢI LÀM          CÓ THỂ LÀM        KHÔNG LÀM
      (MVP)            SAU MVP            (MVP)
          │                │                │
          ▼                ▼                ▼
     Đặt xe           Loyalty           AI Dispatch
Tìm tài xế      Voucher            Dynamic Pricing
     Chuyến đi       Scheduled Ride     Chatbot AI
     Tính cước       Corporate Ride     Ride Sharing
     Thanh toán      Nhiều Payment      Ví điện tử
     Thông báo       Nhiều Channel      BI nâng cao
     Đánh giá        Dịch vụ mới        Navigation riêng
     Admin           Báo cáo nâng cao    CRM đầy đủ
```
# B5. Chuyển đổi yêu cầu thành Business Requirements

| Mã | Tên Business Requirement | Diễn giải |
|---|---|---|
| BR01 | Quản lý tài khoản khách hàng | Hệ thống cho phép khách hàng đăng ký, đăng nhập và quản lý thông tin cá nhân. |
| BR02 | Quản lý tài khoản tài xế | Hệ thống cho phép tạo và quản lý tài khoản, hồ sơ và thông tin hoạt động của tài xế. |
| BR03 | Quản lý phương tiện | Hệ thống cho phép quản lý thông tin phương tiện được sử dụng để thực hiện chuyến đi. |
| BR04 | Quản lý quyền truy cập | Hệ thống cho phép phân quyền cho nhân viên vận hành và quản trị viên theo vai trò. |
| BR05 | Quản lý trạng thái tài xế | Hệ thống cho phép tài xế cập nhật trạng thái hoạt động và trạng thái sẵn sàng nhận chuyến. |
| BR06 | Theo dõi vị trí tài xế | Hệ thống lưu và cập nhật vị trí tài xế để phục vụ việc tìm kiếm và phân công chuyến. |
| BR07 | Tạo yêu cầu đặt xe | Hệ thống cho phép khách hàng nhập điểm đón, điểm đến và lựa chọn loại xe để tạo yêu cầu đặt xe. |
| BR08 | Tiếp nhận yêu cầu đặt xe | Hệ thống tiếp nhận và lưu thông tin yêu cầu đặt xe của khách hàng. |
| BR09 | Tự động tìm tài xế | Hệ thống tự động tìm các tài xế phù hợp dựa trên vị trí, trạng thái sẵn sàng và các tiêu chí vận hành. |
| BR10 | Ưu tiên tài xế phù hợp | Hệ thống ưu tiên tài xế phù hợp và gần khách hàng theo các tiêu chí vận hành được doanh nghiệp xác định. |
| BR11 | Xử lý tài xế từ chối hoặc không phản hồi | Hệ thống tiếp tục tìm tài xế khác khi tài xế được đề xuất từ chối hoặc không phản hồi trong thời gian quy định. |
| BR12 | Thông báo không tìm được tài xế | Hệ thống thông báo rõ ràng cho khách hàng khi không tìm được tài xế phù hợp. |
| BR13 | Phân công tài xế | Hệ thống xác nhận và gán tài xế cho chuyến đi khi tài xế chấp nhận yêu cầu. |
| BR14 | Quản lý trạng thái chuyến đi | Hệ thống quản lý và cập nhật trạng thái chuyến từ lúc tạo yêu cầu đến khi hoàn thành hoặc hủy. |
| BR15 | Theo dõi chuyến đi | Hệ thống cho phép khách hàng theo dõi trạng thái chuyến và thông tin liên quan trong quá trình thực hiện chuyến. |
| BR16 | Theo dõi thời gian dự kiến | Hệ thống cung cấp thời gian dự kiến tài xế đến điểm đón cho khách hàng. |
| BR17 | Xử lý chuyến bị hủy hoặc lỗi | Hệ thống hỗ trợ xử lý các trường hợp chuyến bị hủy hoặc gặp sự cố theo chính sách của doanh nghiệp. |
| BR18 | Lưu lịch sử chuyến đi | Hệ thống lưu trữ thông tin các chuyến đi để khách hàng và nhân viên có thể tra cứu khi cần. |
| BR19 | Tính cước chuyến đi | Hệ thống xác định số tiền khách hàng phải trả dựa trên loại dịch vụ và thông tin chuyến đi. |
| BR20 | Thanh toán tiền mặt | Hệ thống hỗ trợ ghi nhận và quản lý kết quả thanh toán bằng tiền mặt. |
| BR21 | Thanh toán điện tử | Hệ thống hỗ trợ thanh toán điện tử thông qua nhà cung cấp thanh toán bên ngoài. |
| BR22 | Quản lý kết quả thanh toán | Hệ thống tiếp nhận, lưu trữ và cập nhật trạng thái giao dịch thanh toán. |
| BR23 | Xử lý thanh toán thất bại | Hệ thống thông báo cho khách hàng khi thanh toán thất bại và hỗ trợ xử lý lại theo chính sách doanh nghiệp. |
| BR24 | Bảo vệ thông tin thanh toán | Hệ thống không lưu trực tiếp các thông tin nhạy cảm của thẻ hoặc tài khoản thanh toán. |
| BR25 | Quản lý lịch sử giao dịch | Hệ thống lưu trữ và cho phép nhân viên tra cứu lịch sử giao dịch thanh toán. |
| BR26 | Thông báo trạng thái đặt xe | Hệ thống gửi thông báo cho khách hàng khi yêu cầu đặt xe được tiếp nhận và khi trạng thái chuyến thay đổi. |
| BR27 | Thông báo cho tài xế | Hệ thống gửi thông báo cho tài xế khi có chuyến mới hoặc có thay đổi liên quan đến chuyến đang thực hiện. |
| BR28 | Mở rộng kênh thông báo | Hệ thống được thiết kế để có thể bổ sung thêm các kênh thông báo trong tương lai. |
| BR29 | Đánh giá tài xế | Hệ thống cho phép khách hàng đánh giá tài xế sau khi chuyến đi hoàn thành. |
| BR30 | Quản lý phản hồi | Hệ thống lưu trữ thông tin đánh giá và phản hồi của khách hàng đối với tài xế. |
| BR31 | Quản lý khách hàng | Hệ thống cung cấp chức năng cho nhân viên vận hành quản lý và tra cứu thông tin khách hàng. |
| BR32 | Quản lý tài xế và phương tiện | Hệ thống cung cấp chức năng cho nhân viên vận hành quản lý tài xế và phương tiện. |
| BR33 | Theo dõi chuyến đang diễn ra | Hệ thống cho phép nhân viên vận hành theo dõi các chuyến đang thực hiện và trạng thái hiện tại. |
| BR34 | Hỗ trợ xử lý sự cố | Hệ thống cho phép nhân viên vận hành kiểm tra và hỗ trợ xử lý các trường hợp chuyến bị lỗi. |
| BR35 | Báo cáo hoạt động | Hệ thống cung cấp báo cáo về số lượng chuyến, doanh thu, tỷ lệ hoàn thành và tỷ lệ hủy chuyến. |
| BR36 | Báo cáo hiệu quả tài xế | Hệ thống cung cấp dữ liệu và báo cáo để đánh giá hiệu quả hoạt động của tài xế. |
| BR37 | Xác thực người dùng | Hệ thống yêu cầu người dùng xác thực trước khi sử dụng các chức năng yêu cầu tài khoản. |
| BR38 | Kiểm soát quyền truy cập | Hệ thống kiểm soát quyền truy cập dựa trên vai trò và quyền hạn của người dùng. |
| BR39 | Bảo vệ dữ liệu | Hệ thống bảo vệ thông tin cá nhân, thông tin phương tiện, dữ liệu vị trí và dữ liệu giao dịch. |
| BR40 | Lưu vết thao tác | Hệ thống lưu lại các thao tác quan trọng của người dùng và nhân viên để phục vụ kiểm tra, truy vết khi xảy ra sự cố. |
| BR41 | Đảm bảo khả năng mở rộng | Hệ thống được thiết kế để có thể mở rộng số lượng khách hàng, tài xế và các thành phần khi nhu cầu tăng. |
| BR42 | Đảm bảo tính độc lập của các thành phần | Hệ thống hạn chế việc lỗi tại các thành phần như thanh toán hoặc thông báo làm ảnh hưởng đến toàn bộ chức năng đặt xe. |
| BR43 | Hỗ trợ triển khai từng phần | Hệ thống cho phép triển khai các chức năng mới từng phần và hạn chế ảnh hưởng đến các chức năng đang hoạt động. |
| BR44 | Hỗ trợ mở rộng dịch vụ | Kiến trúc hệ thống cho phép bổ sung các loại dịch vụ mới trong tương lai mà không phải xây dựng lại toàn bộ hệ thống. |
| BR45 | Hỗ trợ mở rộng phương thức thanh toán | Hệ thống cho phép tích hợp thêm phương thức hoặc nhà cung cấp thanh toán trong tương lai. |
| BR46 | Hỗ trợ mở rộng nhà cung cấp thông báo | Hệ thống cho phép thay đổi hoặc bổ sung nhà cung cấp thông báo mà không ảnh hưởng lớn đến hệ thống hiện tại. |

# B6: Xây dựng Business Process

## 1. Business Process: Đặt xe

### Mục tiêu

Quy trình cho phép khách hàng tạo yêu cầu đặt xe, hệ thống xác nhận thông tin, tìm tài xế phù hợp và xử lý trường hợp tài xế không nhận chuyến.

### Quy trình

```text
Khách hàng
    |
    v
Đăng nhập hệ thống
    |
    v
Nhập điểm đón và điểm đến
    |
    v
Lựa chọn loại xe / dịch vụ
    |
    v
Tạo yêu cầu chuyến đi
    |
    v
Hệ thống kiểm tra và xác nhận yêu cầu
    |
    +----------------------+
    |                      |
    v                      v
Không hợp lệ            Hợp lệ
    |                      |
    v                      v
Thông báo lỗi        Tìm tài xế phù hợp
                           |
                           v
                  Có tìm thấy tài xế?
                    /             \
                  Không             Có
                   |                |
                   v                v
          Thông báo khách hàng   Gửi thông báo
          không tìm được tài xế  cho tài xế
                                    |
                                    v
                           Tài xế chấp nhận?
                              /          \
                            Không         Có
                             |             |
                             v             v
                    Tìm tài xế khác   Xác nhận chuyến
                             |             |
                             |             v
                             |      Thông báo khách hàng
                             |      tài xế đã nhận chuyến
                             |             |
                             |             v
                             |       Theo dõi chuyến đi
                             |
                             +------> Quay lại bước
                                     tìm tài xế phù hợp
```

---

## 2. Các bước chi tiết

| Bước | Tác nhân   | Hoạt động                                                                                   | Kết quả                                                            |
| ---- | ---------- | ------------------------------------------------------------------------------------------- | ------------------------------------------------------------------ |
| 1    | Khách hàng | Đăng nhập vào hệ thống                                                                      | Khách hàng được xác thực                                           |
| 2    | Khách hàng | Nhập điểm đón và điểm đến                                                                   | Hệ thống nhận thông tin chuyến đi                                  |
| 3    | Khách hàng | Lựa chọn loại xe/dịch vụ                                                                    | Xác định loại dịch vụ khách hàng muốn sử dụng                      |
| 4    | Khách hàng | Gửi yêu cầu đặt xe                                                                          | Yêu cầu đặt xe được tạo                                            |
| 5    | Hệ thống   | Kiểm tra thông tin yêu cầu                                                                  | Xác định yêu cầu hợp lệ hoặc không hợp lệ                          |
| 6    | Hệ thống   | Nếu yêu cầu không hợp lệ, thông báo lỗi cho khách hàng                                      | Khách hàng biết thông tin cần điều chỉnh                           |
| 7    | Hệ thống   | Nếu yêu cầu hợp lệ, bắt đầu tìm tài xế                                                      | Chuyển sang quá trình phân công tài xế                             |
| 8    | Hệ thống   | Xác định tài xế phù hợp dựa trên vị trí, trạng thái sẵn sàng và tiêu chí vận hành           | Xác định có hoặc không có tài xế phù hợp                           |
| 9    | Hệ thống   | Nếu không tìm thấy tài xế, thông báo cho khách hàng                                         | Khách hàng biết hệ thống chưa tìm được tài xế                      |
| 10   | Hệ thống   | Nếu tìm thấy tài xế, gửi yêu cầu chuyến đi cho tài xế phù hợp                               | Tài xế nhận được thông báo                                         |
| 11   | Tài xế     | Xem thông tin chuyến đi và quyết định chấp nhận hoặc từ chối                                | Xác định kết quả phản hồi                                          |
| 12   | Tài xế     | Nếu từ chối hoặc không phản hồi trong thời gian quy định, hệ thống tiếp tục tìm tài xế khác | Không yêu cầu khách hàng tạo lại chuyến                            |
| 13   | Hệ thống   | Nếu tài xế chấp nhận, xác nhận tài xế được phân công cho chuyến                             | Chuyến đi được xác nhận                                            |
| 14   | Hệ thống   | Thông báo cho khách hàng tài xế đã nhận chuyến                                              | Khách hàng biết tài xế, thời gian dự kiến đến và trạng thái chuyến |
| 15   | Tài xế     | Di chuyển đến điểm đón và cập nhật trạng thái                                               | Khách hàng có thể theo dõi trạng thái chuyến                       |

---

## 3. Business Process tổng quát

**Khách hàng tạo chuyến → Hệ thống xác nhận yêu cầu → Tìm tài xế → Kiểm tra tài xế phù hợp → Gửi yêu cầu cho tài xế → Tài xế chấp nhận/từ chối → Nếu từ chối hoặc không phản hồi thì tìm tài xế khác → Nếu chấp nhận thì xác nhận chuyến → Thông báo cho khách hàng → Theo dõi chuyến đi.**

### Các trường hợp ngoại lệ

* **Không tìm thấy tài xế:** Hệ thống thông báo cho khách hàng rằng hiện chưa tìm được tài xế phù hợp.
* **Tài xế từ chối:** Hệ thống tiếp tục tìm tài xế khác mà không yêu cầu khách hàng tạo lại chuyến.
* **Tài xế không phản hồi:** Hệ thống xử lý theo thời gian phản hồi được doanh nghiệp quy định và tiếp tục tìm tài xế khác.
* **Nhiều tài xế phù hợp:** Hệ thống ưu tiên tài xế theo vị trí, trạng thái sẵn sàng và các tiêu chí vận hành.
* **Tài xế chấp nhận:** Hệ thống xác nhận tài xế, cập nhật trạng thái chuyến và thông báo cho khách hàng.

# B7: Thiết kế phân rã yêu cầu nghiệp vụ (Functional Requirement - FR)

## 1. Mục đích

Phân rã các **Business Requirement (BR)** thành các **Functional Requirement (FR)** cụ thể nhằm xác định rõ các chức năng mà hệ thống CAB System cần cung cấp.

---

## 2. Cây phân rã yêu cầu nghiệp vụ

```text
CAB SYSTEM
│
├── BR01: Quản lý tài khoản người dùng
│   ├── FR01.01: Đăng ký tài khoản khách hàng
│   ├── FR01.02: Đăng nhập hệ thống
│   ├── FR01.03: Cập nhật thông tin cá nhân
│   └── FR01.04: Xác thực người dùng
│
├── BR02: Quản lý tài xế
│   ├── FR02.01: Tạo tài khoản tài xế
│   ├── FR02.02: Cập nhật hồ sơ tài xế
│   ├── FR02.03: Quản lý thông tin phương tiện
│   └── FR02.04: Cập nhật trạng thái hoạt động
│
├── BR03: Đặt xe
│   ├── FR03.01: Nhập điểm đón
│   ├── FR03.02: Nhập điểm đến
│   ├── FR03.03: Lựa chọn loại xe/dịch vụ
│   ├── FR03.04: Tạo yêu cầu đặt xe
│   └── FR03.05: Xác nhận yêu cầu đặt xe
│
├── BR04: Tìm kiếm và phân công tài xế
│   ├── FR04.01: Xác định tài xế phù hợp
│   ├── FR04.02: Ưu tiên tài xế gần khách hàng
│   ├── FR04.03: Gửi yêu cầu chuyến đi cho tài xế
│   ├── FR04.04: Xử lý tài xế chấp nhận chuyến
│   ├── FR04.05: Xử lý tài xế từ chối chuyến
│   ├── FR04.06: Xử lý tài xế không phản hồi
│   └── FR04.07: Tìm tài xế khác khi không được chấp nhận
│
├── BR05: Quản lý và theo dõi chuyến đi
│   ├── FR05.01: Cập nhật trạng thái chuyến đi
│   ├── FR05.02: Hiển thị thông tin tài xế
│   ├── FR05.03: Hiển thị thời gian dự kiến tài xế đến
│   ├── FR05.04: Theo dõi vị trí tài xế
│   └── FR05.05: Xem lịch sử chuyến đi
│
├── BR06: Tính cước và thanh toán
│   ├── FR06.01: Tính cước chuyến đi
│   ├── FR06.02: Hiển thị số tiền phải thanh toán
│   ├── FR06.03: Thanh toán bằng tiền mặt
│   ├── FR06.04: Thanh toán điện tử
│   ├── FR06.05: Kết nối nhà cung cấp thanh toán
│   └── FR06.06: Xử lý giao dịch thanh toán thất bại
│
├── BR07: Quản lý thông báo
│   ├── FR07.01: Thông báo tiếp nhận yêu cầu đặt xe
│   ├── FR07.02: Thông báo tài xế nhận chuyến
│   ├── FR07.03: Thông báo tài xế đến điểm đón
│   ├── FR07.04: Thông báo hoàn thành chuyến
│   ├── FR07.05: Thông báo kết quả thanh toán
│   └── FR07.06: Thông báo chuyến mới cho tài xế
│
├── BR08: Đánh giá chuyến đi
│   ├── FR08.01: Cho phép khách hàng đánh giá tài xế
│   ├── FR08.02: Ghi nhận đánh giá
│   └── FR08.03: Xem thông tin đánh giá
│
├── BR09: Quản trị và vận hành
│   ├── FR09.01: Quản lý khách hàng
│   ├── FR09.02: Quản lý tài xế
│   ├── FR09.03: Quản lý phương tiện
│   ├── FR09.04: Theo dõi các chuyến đang diễn ra
│   ├── FR09.05: Tra cứu lịch sử giao dịch
│   ├── FR09.06: Xử lý các chuyến bị lỗi
│   └── FR09.07: Phân quyền nhân viên
│
└── BR10: Báo cáo và thống kê
    ├── FR10.01: Báo cáo số lượng chuyến
    ├── FR10.02: Báo cáo doanh thu
    ├── FR10.03: Báo cáo tỷ lệ chuyến hoàn thành
    ├── FR10.04: Báo cáo tỷ lệ hủy chuyến
    └── FR10.05: Báo cáo hiệu quả hoạt động tài xế
```

---

## 3. Bảng phân rã Business Requirement → Functional Requirement

| Mã BR | Business Requirement          | Mã FR   | Functional Requirement                                                                                  |
| ----- | ----------------------------- | ------- | ------------------------------------------------------------------------------------------------------- |
| BR01  | Quản lý tài khoản người dùng  | FR01.01 | Hệ thống cho phép khách hàng đăng ký tài khoản.                                                         |
| BR01  | Quản lý tài khoản người dùng  | FR01.02 | Hệ thống cho phép người dùng đăng nhập.                                                                 |
| BR01  | Quản lý tài khoản người dùng  | FR01.03 | Hệ thống cho phép người dùng cập nhật thông tin cá nhân.                                                |
| BR01  | Quản lý tài khoản người dùng  | FR01.04 | Hệ thống xác thực người dùng trước khi sử dụng chức năng yêu cầu tài khoản.                             |
| BR02  | Quản lý tài xế                | FR02.01 | Hệ thống cho phép tài xế đăng ký hoặc nhân viên vận hành tạo tài khoản.                                 |
| BR02  | Quản lý tài xế                | FR02.02 | Hệ thống cho phép cập nhật hồ sơ tài xế.                                                                |
| BR02  | Quản lý tài xế                | FR02.03 | Hệ thống cho phép quản lý thông tin phương tiện của tài xế.                                             |
| BR02  | Quản lý tài xế                | FR02.04 | Hệ thống cho phép tài xế cập nhật trạng thái sẵn sàng hoặc không sẵn sàng nhận chuyến.                  |
| BR03  | Đặt xe                        | FR03.01 | Hệ thống cho phép khách hàng nhập điểm đón.                                                             |
| BR03  | Đặt xe                        | FR03.02 | Hệ thống cho phép khách hàng nhập điểm đến.                                                             |
| BR03  | Đặt xe                        | FR03.03 | Hệ thống cho phép khách hàng lựa chọn loại xe/dịch vụ.                                                  |
| BR03  | Đặt xe                        | FR03.04 | Hệ thống cho phép khách hàng tạo yêu cầu đặt xe.                                                        |
| BR03  | Đặt xe                        | FR03.05 | Hệ thống kiểm tra và xác nhận thông tin yêu cầu đặt xe.                                                 |
| BR04  | Tìm kiếm và phân công tài xế  | FR04.01 | Hệ thống xác định các tài xế phù hợp với yêu cầu chuyến đi.                                             |
| BR04  | Tìm kiếm và phân công tài xế  | FR04.02 | Hệ thống ưu tiên tài xế phù hợp và gần vị trí khách hàng.                                               |
| BR04  | Tìm kiếm và phân công tài xế  | FR04.03 | Hệ thống gửi thông báo yêu cầu chuyến đi đến tài xế được đề xuất.                                       |
| BR04  | Tìm kiếm và phân công tài xế  | FR04.04 | Hệ thống ghi nhận khi tài xế chấp nhận chuyến.                                                          |
| BR04  | Tìm kiếm và phân công tài xế  | FR04.05 | Hệ thống ghi nhận khi tài xế từ chối chuyến.                                                            |
| BR04  | Tìm kiếm và phân công tài xế  | FR04.06 | Hệ thống xử lý trường hợp tài xế không phản hồi.                                                        |
| BR04  | Tìm kiếm và phân công tài xế  | FR04.07 | Hệ thống tiếp tục tìm tài xế khác khi tài xế được đề xuất không nhận chuyến.                            |
| BR05  | Quản lý và theo dõi chuyến đi | FR05.01 | Hệ thống cho phép cập nhật trạng thái chuyến đi.                                                        |
| BR05  | Quản lý và theo dõi chuyến đi | FR05.02 | Hệ thống hiển thị thông tin tài xế cho khách hàng.                                                      |
| BR05  | Quản lý và theo dõi chuyến đi | FR05.03 | Hệ thống hiển thị thời gian dự kiến tài xế đến điểm đón.                                                |
| BR05  | Quản lý và theo dõi chuyến đi | FR05.04 | Hệ thống ghi nhận và hỗ trợ theo dõi vị trí tài xế.                                                     |
| BR05  | Quản lý và theo dõi chuyến đi | FR05.05 | Hệ thống cho phép khách hàng xem lịch sử chuyến đi.                                                     |
| BR06  | Tính cước và thanh toán       | FR06.01 | Hệ thống tính số tiền phải trả dựa trên thông tin chuyến đi và loại dịch vụ.                            |
| BR06  | Tính cước và thanh toán       | FR06.02 | Hệ thống hiển thị số tiền khách hàng phải thanh toán.                                                   |
| BR06  | Tính cước và thanh toán       | FR06.03 | Hệ thống hỗ trợ thanh toán bằng tiền mặt.                                                               |
| BR06  | Tính cước và thanh toán       | FR06.04 | Hệ thống hỗ trợ thanh toán điện tử.                                                                     |
| BR06  | Tính cước và thanh toán       | FR06.05 | Hệ thống tích hợp với nhà cung cấp dịch vụ thanh toán bên ngoài.                                        |
| BR06  | Tính cước và thanh toán       | FR06.06 | Hệ thống thông báo và xử lý lại giao dịch khi thanh toán điện tử thất bại theo chính sách doanh nghiệp. |
| BR07  | Quản lý thông báo             | FR07.01 | Hệ thống thông báo khi yêu cầu đặt xe được tiếp nhận.                                                   |
| BR07  | Quản lý thông báo             | FR07.02 | Hệ thống thông báo khi tài xế nhận chuyến.                                                              |
| BR07  | Quản lý thông báo             | FR07.03 | Hệ thống thông báo khi tài xế đến điểm đón.                                                             |
| BR07  | Quản lý thông báo             | FR07.04 | Hệ thống thông báo khi chuyến đi hoàn thành.                                                            |
| BR07  | Quản lý thông báo             | FR07.05 | Hệ thống thông báo kết quả thanh toán.                                                                  |
| BR07  | Quản lý thông báo             | FR07.06 | Hệ thống thông báo cho tài xế khi có chuyến mới hoặc thay đổi liên quan đến chuyến đang thực hiện.      |
| BR08  | Đánh giá chuyến đi            | FR08.01 | Hệ thống cho phép khách hàng đánh giá tài xế sau khi hoàn thành chuyến.                                 |
| BR08  | Đánh giá chuyến đi            | FR08.02 | Hệ thống lưu trữ đánh giá của khách hàng.                                                               |
| BR08  | Đánh giá chuyến đi            | FR08.03 | Hệ thống cho phép tra cứu thông tin đánh giá theo quyền được cấp.                                       |
| BR09  | Quản trị và vận hành          | FR09.01 | Nhân viên vận hành có thể quản lý thông tin khách hàng.                                                 |
| BR09  | Quản trị và vận hành          | FR09.02 | Nhân viên vận hành có thể quản lý thông tin tài xế.                                                     |
| BR09  | Quản trị và vận hành          | FR09.03 | Nhân viên vận hành có thể quản lý thông tin phương tiện.                                                |
| BR09  | Quản trị và vận hành          | FR09.04 | Nhân viên vận hành có thể xem và theo dõi các chuyến đang diễn ra.                                      |
| BR09  | Quản trị và vận hành          | FR09.05 | Nhân viên vận hành có thể tra cứu lịch sử giao dịch.                                                    |
| BR09  | Quản trị và vận hành          | FR09.06 | Nhân viên vận hành có thể hỗ trợ xử lý các chuyến bị lỗi.                                               |
| BR09  | Quản trị và vận hành          | FR09.07 | Hệ thống cho phép phân quyền các chức năng quản trị.                                                    |
| BR10  | Báo cáo và thống kê           | FR10.01 | Hệ thống cung cấp báo cáo số lượng chuyến.                                                              |
| BR10  | Báo cáo và thống kê           | FR10.02 | Hệ thống cung cấp báo cáo doanh thu.                                                                    |
| BR10  | Báo cáo và thống kê           | FR10.03 | Hệ thống cung cấp báo cáo tỷ lệ chuyến hoàn thành.                                                      |
| BR10  | Báo cáo và thống kê           | FR10.04 | Hệ thống cung cấp báo cáo tỷ lệ hủy chuyến.                                                             |
| BR10  | Báo cáo và thống kê           | FR10.05 | Hệ thống cung cấp báo cáo hiệu quả hoạt động của tài xế.                                                |

---

## 4. Tổng kết

Hệ thống CAB được phân rã thành **10 nhóm Business Requirement (BR)** và **49 Functional Requirement (FR)**.

Các nhóm chức năng chính gồm:

1. Quản lý tài khoản người dùng.
2. Quản lý tài xế.
3. Đặt xe.
4. Tìm kiếm và phân công tài xế.
5. Quản lý và theo dõi chuyến đi.
6. Tính cước và thanh toán.
7. Quản lý thông báo.
8. Đánh giá chuyến đi.
9. Quản trị và vận hành.
10. Báo cáo và thống kê.

> **Lưu ý:** Các vấn đề như cách tính cước cụ thể, tiêu chí ưu tiên tài xế, thời gian phản hồi, chính sách hủy chuyến và xử lý mất kết nối vẫn là các nội dung cần BA xác nhận thêm với khách hàng trước khi đặc tả FR ở mức chi tiết.

# B8: Business Rules và Acceptance Criteria

## 1. Business Rules – Quy định nghiệp vụ

| Mã    | Quy định nghiệp vụ                                                                                                                    |
| ----- | ------------------------------------------------------------------------------------------------------------------------------------- |
| BRL01 | Khách hàng phải đăng nhập trước khi thực hiện các chức năng đặt xe.                                                                   |
| BRL02 | Khách hàng phải nhập đầy đủ điểm đón và điểm đến trước khi tạo chuyến đi.                                                             |
| BRL03 | Khách hàng phải lựa chọn loại xe/dịch vụ trước khi gửi yêu cầu đặt xe.                                                                |
| BRL04 | Chuyến đi chỉ được tạo khi thông tin đặt xe hợp lệ.                                                                                   |
| BRL05 | Tài xế phải ở trạng thái **sẵn sàng** mới được hệ thống đề xuất nhận chuyến.                                                          |
| BRL06 | Tài xế phải có phương tiện hợp lệ và phù hợp với loại dịch vụ của chuyến đi.                                                          |
| BRL07 | Hệ thống ưu tiên tài xế phù hợp và gần vị trí khách hàng.                                                                             |
| BRL08 | Tài xế có quyền chấp nhận hoặc từ chối yêu cầu chuyến đi.                                                                             |
| BRL09 | Nếu tài xế từ chối chuyến, hệ thống phải tiếp tục tìm tài xế phù hợp khác.                                                            |
| BRL10 | Nếu tài xế không phản hồi trong thời gian quy định, hệ thống phải xử lý như trường hợp không nhận chuyến và tiếp tục tìm tài xế khác. |
| BRL11 | Nếu không tìm được tài xế phù hợp, hệ thống phải thông báo rõ ràng cho khách hàng.                                                    |
| BRL12 | Chỉ tài xế được phân công cho chuyến mới được phép cập nhật trạng thái của chuyến đó.                                                 |
| BRL13 | Tài xế phải cập nhật trạng thái theo đúng trình tự của chuyến đi.                                                                     |
| BRL14 | Chuyến đi chỉ được chuyển sang trạng thái hoàn thành khi tài xế xác nhận đã hoàn thành chuyến.                                        |
| BRL15 | Cước chuyến đi phải được tính dựa trên loại dịch vụ và thông tin chuyến đi theo chính sách của doanh nghiệp.                          |
| BRL16 | Khách hàng có thể thanh toán bằng tiền mặt hoặc phương thức thanh toán điện tử được hệ thống hỗ trợ.                                  |
| BRL17 | Thông tin nhạy cảm của thẻ hoặc tài khoản thanh toán không được lưu trực tiếp trong hệ thống CAB.                                     |
| BRL18 | Giao dịch thanh toán điện tử thất bại phải được thông báo cho khách hàng và xử lý lại theo chính sách doanh nghiệp.                   |
| BRL19 | Khách hàng chỉ được đánh giá tài xế sau khi chuyến đi hoàn thành.                                                                     |
| BRL20 | Hệ thống phải gửi thông báo cho khách hàng khi có các sự kiện quan trọng của chuyến đi.                                               |
| BRL21 | Tài xế phải nhận được thông báo khi có chuyến mới hoặc thay đổi liên quan đến chuyến đang thực hiện.                                  |
| BRL22 | Nhân viên chỉ được thực hiện các chức năng quản trị phù hợp với quyền được cấp.                                                       |
| BRL23 | Các thao tác quản trị quan trọng phải được ghi nhận vào nhật ký hệ thống.                                                             |
| BRL24 | Dữ liệu cá nhân, dữ liệu vị trí và dữ liệu giao dịch phải được bảo vệ khỏi truy cập trái phép.                                        |
| BRL25 | Tài xế chỉ được nhận chuyến phù hợp với loại phương tiện và trạng thái hoạt động của mình.                                            |

---

# 2. Acceptance Criteria – Điều kiện nghiệm thu

| Mã   | Chức năng             | Acceptance Criteria                                                                                             |
| ---- | --------------------- | --------------------------------------------------------------------------------------------------------------- |
| AC01 | Đăng nhập             | Khi người dùng nhập đúng thông tin tài khoản, hệ thống cho phép đăng nhập và truy cập chức năng tương ứng.      |
| AC02 | Đăng nhập             | Khi thông tin đăng nhập không hợp lệ, hệ thống từ chối đăng nhập và thông báo lỗi.                              |
| AC03 | Tạo chuyến            | Khi khách hàng nhập đầy đủ điểm đón, điểm đến và loại xe, hệ thống cho phép tạo yêu cầu đặt xe.                 |
| AC04 | Tạo chuyến            | Khi thiếu điểm đón hoặc điểm đến, hệ thống không cho phép tạo chuyến và yêu cầu khách hàng bổ sung thông tin.   |
| AC05 | Tìm tài xế            | Khi có tài xế đang **sẵn sàng** và phù hợp, hệ thống gửi yêu cầu chuyến đi đến tài xế đó.                       |
| AC06 | Tìm tài xế            | Khi không có tài xế phù hợp, hệ thống thông báo cho khách hàng rằng chưa tìm được tài xế.                       |
| AC07 | Tài xế nhận chuyến    | Khi tài xế đang ở trạng thái sẵn sàng và chấp nhận chuyến, hệ thống xác nhận tài xế được phân công.             |
| AC08 | Tài xế từ chối        | Khi tài xế từ chối chuyến, hệ thống tiếp tục tìm tài xế khác mà không yêu cầu khách hàng tạo lại chuyến.        |
| AC09 | Tài xế không phản hồi | Khi tài xế không phản hồi trong thời gian quy định, hệ thống chuyển sang tìm tài xế khác.                       |
| AC10 | Thông báo             | Khi tài xế chấp nhận chuyến, khách hàng nhận được thông báo về tài xế đã nhận chuyến.                           |
| AC11 | Theo dõi chuyến       | Khi tài xế cập nhật trạng thái chuyến, trạng thái mới được hiển thị cho khách hàng theo quyền được phép.        |
| AC12 | Hoàn thành chuyến     | Khi tài xế xác nhận hoàn thành chuyến, hệ thống cập nhật chuyến sang trạng thái hoàn thành.                     |
| AC13 | Tính cước             | Khi chuyến đi hoàn thành, hệ thống tính và hiển thị số tiền khách hàng phải thanh toán.                         |
| AC14 | Thanh toán            | Khi thanh toán điện tử thành công, hệ thống ghi nhận giao dịch thành công và thông báo cho khách hàng.          |
| AC15 | Thanh toán thất bại   | Khi thanh toán điện tử thất bại, hệ thống thông báo kết quả và cho phép xử lý lại theo chính sách doanh nghiệp. |
| AC16 | Đánh giá              | Khi chuyến đi đã hoàn thành, khách hàng có thể đánh giá tài xế.                                                 |
| AC17 | Đánh giá              | Khi chuyến đi chưa hoàn thành, hệ thống không cho phép khách hàng đánh giá tài xế.                              |
| AC18 | Phân quyền            | Nhân viên không có quyền quản trị không thể thực hiện các thao tác nhạy cảm.                                    |
| AC19 | Nhật ký               | Khi người dùng thực hiện thao tác quản trị quan trọng, hệ thống ghi nhận thao tác vào nhật ký.                  |
| AC20 | Bảo mật               | Người dùng chưa xác thực không thể truy cập các chức năng yêu cầu đăng nhập.                                    |

---

# 3. Ví dụ Business Rule → Acceptance Criteria

### Ví dụ 1: Trạng thái tài xế

**Business Rule:**

> `BRL05: Tài xế phải ở trạng thái Sẵn sàng mới được hệ thống đề xuất nhận chuyến.`

**Acceptance Criteria:**

> `AC05: Khi hệ thống tìm tài xế, chỉ những tài xế đang ở trạng thái Sẵn sàng và phù hợp với chuyến đi mới được đưa vào danh sách đề xuất.`

---

### Ví dụ 2: Tài xế từ chối chuyến

**Business Rule:**

> `BRL09: Nếu tài xế từ chối chuyến, hệ thống phải tiếp tục tìm tài xế khác.`

**Acceptance Criteria:**

> `AC08: Khi tài xế từ chối yêu cầu, hệ thống tự động tìm tài xế phù hợp tiếp theo và khách hàng không cần tạo lại yêu cầu.`

---

### Ví dụ 3: Không tìm được tài xế

**Business Rule:**

> `BRL11: Nếu không tìm được tài xế phù hợp, hệ thống phải thông báo cho khách hàng.`

**Acceptance Criteria:**

> `AC06: Khi hệ thống không tìm được tài xế phù hợp, khách hàng nhận được thông báo rằng yêu cầu đặt xe chưa tìm được tài xế.`

---

## 4. Các Business Rule cần xác nhận thêm

Một số quy định chưa được khách hàng xác định cụ thể, BA cần xác nhận trước khi phát triển:

| Nội dung cần xác nhận     | Câu hỏi cần làm rõ                                                                           |
| ------------------------- | -------------------------------------------------------------------------------------------- |
| Thời gian phản hồi tài xế | Tài xế có bao nhiêu giây/phút để chấp nhận hoặc từ chối chuyến?                              |
| Tiêu chí ưu tiên          | Hệ thống ưu tiên tài xế dựa trên khoảng cách, thời gian chờ, đánh giá hay tiêu chí nào khác? |
| Tính cước                 | Cước được tính dựa trên khoảng cách, thời gian, loại xe hay kết hợp nhiều yếu tố?            |
| Hủy chuyến                | Khách hàng và tài xế được hủy chuyến trong những trường hợp nào?                             |
| Phí hủy                   | Có áp dụng phí khi khách hàng hoặc tài xế hủy chuyến hay không?                              |
| Thanh toán thất bại       | Khách hàng được thử thanh toán lại bao nhiêu lần?                                            |
| Mất kết nối               | Hệ thống xử lý thế nào khi khách hàng hoặc tài xế mất kết nối mạng?                          |
| Lưu trữ dữ liệu           | Dữ liệu chuyến đi, giao dịch và nhật ký được lưu trong bao lâu?                              |

# B9: Xác định thực thể và sơ đồ ERD

## 1. Xác định các thực thể

| STT | Thực thể          | Mô tả                                                                |
| --- | ----------------- | -------------------------------------------------------------------- |
| 1   | **KhachHang**     | Lưu thông tin tài khoản và thông tin cá nhân của khách hàng.         |
| 2   | **TaiXe**         | Lưu thông tin tài khoản, hồ sơ và trạng thái hoạt động của tài xế.   |
| 3   | **PhuongTien**    | Lưu thông tin phương tiện mà tài xế sử dụng.                         |
| 4   | **LoaiXe**        | Lưu các loại xe/dịch vụ mà hệ thống cung cấp.                        |
| 5   | **ChuyenDi**      | Lưu thông tin yêu cầu và quá trình thực hiện chuyến đi.              |
| 6   | **DiaDiem**       | Lưu thông tin điểm đón và điểm đến của chuyến đi.                    |
| 7   | **PhanCongTaiXe** | Lưu thông tin quá trình hệ thống tìm và phân công tài xế cho chuyến. |
| 8   | **ThanhToan**     | Lưu thông tin và trạng thái thanh toán của chuyến đi.                |
| 9   | **DanhGia**       | Lưu đánh giá của khách hàng đối với tài xế sau chuyến đi.            |
| 10  | **ThongBao**      | Lưu các thông báo gửi đến khách hàng hoặc tài xế.                    |
| 11  | **NhanVien**      | Lưu thông tin nhân viên vận hành hệ thống.                           |
| 12  | **VaiTro**        | Lưu các vai trò và quyền hạn của nhân viên.                          |
| 13  | **NhatKyHeThong** | Lưu vết các thao tác quan trọng trong hệ thống.                      |

---

## 2. Các thuộc tính chính của thực thể

### KhachHang

* **MaKH** (PK)
* HoTen
* Email
* SoDienThoai
* MatKhau
* DiaChi
* TrangThai

### TaiXe

* **MaTX** (PK)
* HoTen
* Email
* SoDienThoai
* MatKhau
* TrangThaiHoatDong
* ViTriHienTai
* NgayDangKy

### PhuongTien

* **MaPT** (PK)
* MaTX (FK)
* MaLoaiXe (FK)
* BienSo
* HangXe
* MauXe
* TrangThai

### LoaiXe

* **MaLoaiXe** (PK)
* TenLoaiXe
* MoTa
* DonGiaCoBan

### ChuyenDi

* **MaChuyen** (PK)
* MaKH (FK)
* MaLoaiXe (FK)
* MaDiemDon (FK)
* MaDiemDen (FK)
* ThoiGianTao
* ThoiGianBatDau
* ThoiGianKetThuc
* TrangThai
* SoTien

### DiaDiem

* **MaDiaDiem** (PK)
* DiaChi
* ViDo
* KinhDo

### PhanCongTaiXe

* **MaPhanCong** (PK)
* MaChuyen (FK)
* MaTX (FK)
* ThoiGianGui
* ThoiGianPhanHoi
* TrangThaiPhanCong

### ThanhToan

* **MaThanhToan** (PK)
* MaChuyen (FK)
* PhuongThuc
* SoTien
* ThoiGianThanhToan
* TrangThai
* MaGiaoDich

### DanhGia

* **MaDanhGia** (PK)
* MaChuyen (FK)
* MaKH (FK)
* MaTX (FK)
* Diem
* NoiDung
* ThoiGianDanhGia

### ThongBao

* **MaThongBao** (PK)
* MaKH (FK, nullable)
* MaTX (FK, nullable)
* MaChuyen (FK, nullable)
* LoaiThongBao
* NoiDung
* ThoiGianGui
* TrangThaiDoc

### NhanVien

* **MaNV** (PK)
* MaVaiTro (FK)
* HoTen
* Email
* MatKhau
* TrangThai

### VaiTro

* **MaVaiTro** (PK)
* TenVaiTro
* MoTa

### NhatKyHeThong

* **MaNhatKy** (PK)
* MaNV (FK)
* HanhDong
* DoiTuong
* ThoiGian
* NoiDung
* DiaChiIP

---

# 3. Mối quan hệ giữa các thực thể

| Thực thể 1 | Quan hệ             | Thực thể 2         | Cardinality |
| ---------- | ------------------- | ------------------ | ----------- |
| KhachHang  | tạo                 | ChuyenDi           | 1:N         |
| LoaiXe     | được lựa chọn trong | ChuyenDi           | 1:N         |
| LoaiXe     | phân loại           | PhuongTien         | 1:N         |
| TaiXe      | sở hữu/sử dụng      | PhuongTien         | 1:1         |
| ChuyenDi   | có                  | DiaDiem (điểm đón) | N:1         |
| ChuyenDi   | có                  | DiaDiem (điểm đến) | N:1         |
| ChuyenDi   | có quá trình        | PhanCongTaiXe      | 1:N         |
| TaiXe      | nhận/phản hồi       | PhanCongTaiXe      | 1:N         |
| ChuyenDi   | có                  | ThanhToan          | 1:N         |
| KhachHang  | thực hiện           | DanhGia            | 1:N         |
| TaiXe      | nhận                | DanhGia            | 1:N         |
| ChuyenDi   | được đánh giá       | DanhGia            | 1:0..1      |
| KhachHang  | nhận                | ThongBao           | 1:N         |
| TaiXe      | nhận                | ThongBao           | 1:N         |
| ChuyenDi   | phát sinh           | ThongBao           | 1:N         |
| VaiTro     | được gán cho        | NhanVien           | 1:N         |
| NhanVien   | tạo                 | NhatKyHeThong      | 1:N         |

---

# 4. Sơ đồ ERD

Có thể sử dụng Mermaid để vẽ ERD trực tiếp trên GitHub:

```mermaid
erDiagram

    KHACH_HANG ||--o{ CHUYEN_DI : "tao"

    LOAI_XE ||--o{ CHUYEN_DI : "duoc_chon"
    LOAI_XE ||--o{ PHUONG_TIEN : "phan_loai"

    TAI_XE ||--o| PHUONG_TIEN : "su_dung"

    DIA_DIEM ||--o{ CHUYEN_DI : "diem_don"
    DIA_DIEM ||--o{ CHUYEN_DI : "diem_den"

    CHUYEN_DI ||--o{ PHAN_CONG_TAI_XE : "co"
    TAI_XE ||--o{ PHAN_CONG_TAI_XE : "nhan"

    CHUYEN_DI ||--o{ THANH_TOAN : "co"

    KHACH_HANG ||--o{ DANH_GIA : "tao"
    TAI_XE ||--o{ DANH_GIA : "nhan"
    CHUYEN_DI ||--o| DANH_GIA : "duoc_danh_gia"

    KHACH_HANG ||--o{ THONG_BAO : "nhan"
    TAI_XE ||--o{ THONG_BAO : "nhan"
    CHUYEN_DI ||--o{ THONG_BAO : "phat_sinh"

    VAI_TRO ||--o{ NHAN_VIEN : "duoc_gan"

    NHAN_VIEN ||--o{ NHAT_KY_HE_THONG : "tao"

    KHACH_HANG {
        int MaKH PK
        string HoTen
        string Email
        string SoDienThoai
        string MatKhau
        string DiaChi
        string TrangThai
    }

    TAI_XE {
        int MaTX PK
        string HoTen
        string Email
        string SoDienThoai
        string MatKhau
        string TrangThaiHoatDong
        decimal ViTriHienTai
        date NgayDangKy
    }

    PHUONG_TIEN {
        int MaPT PK
        int MaTX FK
        int MaLoaiXe FK
        string BienSo
        string HangXe
        string MauXe
        string TrangThai
    }

    LOAI_XE {
        int MaLoaiXe PK
        string TenLoaiXe
        string MoTa
        decimal DonGiaCoBan
    }

    CHUYEN_DI {
        int MaChuyen PK
        int MaKH FK
        int MaLoaiXe FK
        int MaDiemDon FK
        int MaDiemDen FK
        datetime ThoiGianTao
        datetime ThoiGianBatDau
        datetime ThoiGianKetThuc
        string TrangThai
        decimal SoTien
    }

    DIA_DIEM {
        int MaDiaDiem PK
        string DiaChi
        decimal ViDo
        decimal KinhDo
    }

    PHAN_CONG_TAI_XE {
        int MaPhanCong PK
        int MaChuyen FK
        int MaTX FK
        datetime ThoiGianGui
        datetime ThoiGianPhanHoi
        string TrangThaiPhanCong
    }

    THANH_TOAN {
        int MaThanhToan PK
        int MaChuyen FK
        string PhuongThuc
        decimal SoTien
        datetime ThoiGianThanhToan
        string TrangThai
        string MaGiaoDich
    }

    DANH_GIA {
        int MaDanhGia PK
        int MaChuyen FK
        int MaKH FK
        int MaTX FK
        int Diem
        string NoiDung
        datetime ThoiGianDanhGia
    }

    THONG_BAO {
        int MaThongBao PK
        int MaKH FK
        int MaTX FK
        int MaChuyen FK
        string LoaiThongBao
        string NoiDung
        datetime ThoiGianGui
        string TrangThaiDoc
    }

    NHAN_VIEN {
        int MaNV PK
        int MaVaiTro FK
        string HoTen
        string Email
        string MatKhau
        string TrangThai
    }

    VAI_TRO {
        int MaVaiTro PK
        string TenVaiTro
        string MoTa
    }

    NHAT_KY_HE_THONG {
        int MaNhatKy PK
        int MaNV FK
        string HanhDong
        string DoiTuong
        datetime ThoiGian
        string NoiDung
        string DiaChiIP
    }
```

## 5. Giải thích quan hệ quan trọng

### Khách hàng → Chuyến đi

Một **khách hàng có thể tạo nhiều chuyến đi**, nhưng mỗi chuyến đi chỉ thuộc về một khách hàng.

```text
KHACH_HANG (1) ───────── (N) CHUYEN_DI
```

### Chuyến đi → Phân công tài xế

Một chuyến có thể được gửi cho **nhiều tài xế lần lượt** nếu tài xế trước từ chối hoặc không phản hồi.

```text
CHUYEN_DI (1) ───────── (N) PHAN_CONG_TAI_XE (N) ───────── (1) TAI_XE
```

Đây là quan hệ quan trọng vì nó phản ánh đúng Business Process ở B6.

### Chuyến đi → Thanh toán

Một chuyến có thể phát sinh một hoặc nhiều bản ghi thanh toán trong trường hợp thanh toán thất bại và thực hiện lại.

```text
CHUYEN_DI (1) ───────── (N) THANH_TOAN
```

### Chuyến đi → Đánh giá

Sau khi chuyến hoàn thành, khách hàng có thể đánh giá tài xế.

```text
CHUYEN_DI (1) ───────── (0..1) DANH_GIA
```

### Tài xế → Phương tiện

Mỗi tài xế sử dụng một phương tiện trong phạm vi mô hình hiện tại.

```text
TAI_XE (1) ───────── (1) PHUONG_TIEN
```

> **Lưu ý:** Nếu doanh nghiệp cho phép một tài xế sử dụng nhiều phương tiện, quan hệ này cần đổi thành **1:N** và bổ sung quy định phương tiện nào đang được sử dụng.

# B10: Non-Functional Requirements (NFR)

## 1. Danh sách yêu cầu phi chức năng

| Mã    | Nhóm                       | Non-Functional Requirement                                                                                              |
| ----- | -------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| NFR01 | Hiệu năng                  | Hệ thống phải phản hồi các thao tác thông thường của người dùng trong thời gian phù hợp, hạn chế tình trạng chờ lâu.    |
| NFR02 | Hiệu năng                  | Hệ thống phải có khả năng xử lý đồng thời nhiều yêu cầu đặt xe trong thời gian cao điểm.                                |
| NFR03 | Hiệu năng                  | Thông tin trạng thái chuyến đi và vị trí tài xế phải được cập nhật với độ trễ thấp.                                     |
| NFR04 | Khả năng mở rộng           | Hệ thống phải có khả năng mở rộng khi số lượng khách hàng, tài xế và chuyến đi tăng lên.                                |
| NFR05 | Khả năng mở rộng           | Các thành phần như đặt xe, thanh toán và thông báo phải có khả năng mở rộng độc lập khi tải tăng.                       |
| NFR06 | Tính sẵn sàng              | Hệ thống phải hoạt động ổn định và hạn chế gián đoạn trong thời gian nhu cầu đặt xe cao.                                |
| NFR07 | Độ tin cậy                 | Lỗi tại một thành phần như thanh toán hoặc thông báo không được làm toàn bộ hệ thống đặt xe ngừng hoạt động.            |
| NFR08 | Khả năng phục hồi          | Hệ thống phải có khả năng xử lý và phục hồi khi xảy ra lỗi kết nối hoặc lỗi từ các dịch vụ bên ngoài.                   |
| NFR09 | Bảo mật                    | Người dùng phải được xác thực trước khi truy cập các chức năng yêu cầu tài khoản.                                       |
| NFR10 | Bảo mật                    | Hệ thống phải kiểm soát quyền truy cập đối với các chức năng quản trị.                                                  |
| NFR11 | Bảo mật                    | Thông tin cá nhân của khách hàng và tài xế phải được bảo vệ khỏi truy cập trái phép.                                    |
| NFR12 | Bảo mật                    | Dữ liệu vị trí của tài xế phải được bảo vệ và chỉ cung cấp cho các đối tượng có quyền truy cập.                         |
| NFR13 | Bảo mật                    | Dữ liệu giao dịch phải được bảo vệ trong quá trình truyền và lưu trữ.                                                   |
| NFR14 | Bảo mật                    | Thông tin nhạy cảm của thẻ hoặc tài khoản thanh toán không được lưu trực tiếp trong hệ thống CAB.                       |
| NFR15 | Audit                      | Các thao tác quản trị và thao tác quan trọng phải được ghi lại để phục vụ kiểm tra và điều tra sự cố.                   |
| NFR16 | Khả năng bảo trì           | Hệ thống phải có kiến trúc cho phép thay đổi hoặc nâng cấp từng thành phần mà hạn chế ảnh hưởng đến các chức năng khác. |
| NFR17 | Khả năng mở rộng chức năng | Hệ thống phải cho phép bổ sung loại dịch vụ mới mà không phải xây dựng lại toàn bộ ứng dụng.                            |
| NFR18 | Khả năng mở rộng chức năng | Hệ thống phải cho phép tích hợp thêm phương thức thanh toán trong tương lai.                                            |
| NFR19 | Khả năng mở rộng chức năng | Hệ thống phải cho phép tích hợp thêm các nhà cung cấp dịch vụ thông báo.                                                |
| NFR20 | Tương thích                | Hệ thống phải có khả năng tích hợp với các dịch vụ bên ngoài như nhà cung cấp thanh toán và dịch vụ thông báo.          |
| NFR21 | Triển khai                 | Các chức năng mới phải có thể được triển khai từng phần và hạn chế ảnh hưởng đến các chức năng đang hoạt động.          |
| NFR22 | Tính toàn vẹn dữ liệu      | Dữ liệu chuyến đi, thanh toán, tài xế và khách hàng phải được lưu trữ chính xác và nhất quán.                           |
| NFR23 | Khả năng sử dụng           | Giao diện phải dễ sử dụng để khách hàng có thể nhanh chóng tạo và theo dõi chuyến đi.                                   |
| NFR24 | Khả năng sử dụng           | Giao diện vận hành phải giúp nhân viên dễ dàng theo dõi chuyến đang diễn ra, tài xế và các trường hợp lỗi.              |
| NFR25 | Khả năng phục vụ           | Hệ thống phải hỗ trợ số lượng lớn khách hàng và tài xế đồng thời mà vẫn duy trì hiệu năng phù hợp.                      |

---

## 2. Phân loại Non-Functional Requirement

### 2.1. Performance – Hiệu năng

* **NFR01:** Phản hồi nhanh đối với các thao tác thông thường.
* **NFR02:** Xử lý được nhiều yêu cầu đặt xe đồng thời.
* **NFR03:** Cập nhật trạng thái chuyến và vị trí tài xế với độ trễ thấp.

### 2.2. Scalability – Khả năng mở rộng

* **NFR04:** Mở rộng khi số lượng người dùng và chuyến đi tăng.
* **NFR05:** Các thành phần có thể mở rộng độc lập.
* **NFR17:** Có thể bổ sung loại dịch vụ mới.
* **NFR18:** Có thể bổ sung phương thức thanh toán.
* **NFR19:** Có thể bổ sung nhà cung cấp thông báo.

### 2.3. Security – Bảo mật

* **NFR09:** Xác thực người dùng.
* **NFR10:** Phân quyền quản trị.
* **NFR11:** Bảo vệ thông tin cá nhân.
* **NFR12:** Bảo vệ dữ liệu vị trí.
* **NFR13:** Bảo vệ dữ liệu giao dịch.
* **NFR14:** Không lưu thông tin nhạy cảm của phương thức thanh toán.

### 2.4. Reliability & Availability – Độ tin cậy và tính sẵn sàng

* **NFR06:** Hệ thống hoạt động ổn định trong giờ cao điểm.
* **NFR07:** Lỗi thanh toán/thông báo không làm dừng toàn bộ hệ thống.
* **NFR08:** Có khả năng phục hồi khi dịch vụ bên ngoài hoặc kết nối gặp lỗi.

### 2.5. Maintainability – Khả năng bảo trì

* **NFR16:** Có thể thay đổi từng thành phần độc lập.
* **NFR21:** Có thể triển khai chức năng mới từng phần.

### 2.6. Audit & Data Integrity – Kiểm tra và toàn vẹn dữ liệu

* **NFR15:** Ghi nhận các thao tác quan trọng.
* **NFR22:** Đảm bảo dữ liệu chính xác và nhất quán.

### 2.7. Usability – Khả năng sử dụng

* **NFR23:** Giao diện khách hàng dễ sử dụng.
* **NFR24:** Giao diện vận hành dễ theo dõi và quản lý.
* **NFR25:** Phục vụ được số lượng lớn người dùng đồng thời.

---

## 3. Các NFR cần xác nhận với khách hàng

Một số NFR trong tài liệu hiện chưa có con số cụ thể. BA cần xác nhận trước khi chuyển sang giai đoạn thiết kế chi tiết:

| Nội dung                | Cần xác nhận                                                     |
| ----------------------- | ---------------------------------------------------------------- |
| Thời gian phản hồi      | Hệ thống phải phản hồi trong tối đa bao nhiêu giây?              |
| Số người dùng đồng thời | Hệ thống cần hỗ trợ tối đa bao nhiêu khách hàng/tài xế cùng lúc? |
| Thời gian hoạt động     | Hệ thống yêu cầu mức uptime bao nhiêu %?                         |
| Cập nhật vị trí         | Vị trí tài xế cần được cập nhật mỗi bao nhiêu giây?              |
| Thời gian phục hồi      | Khi xảy ra lỗi, hệ thống phải phục hồi trong tối đa bao lâu?     |
| Lưu trữ dữ liệu         | Dữ liệu chuyến đi, giao dịch và nhật ký được lưu trong bao lâu?  |
| Bảo mật                 | Doanh nghiệp yêu cầu những tiêu chuẩn bảo mật nào?               |
| Sao lưu                 | Dữ liệu được sao lưu với tần suất như thế nào?                   |

> **Kết luận:** CAB System cần đặc biệt chú trọng **Performance, Scalability, Security, Availability, Reliability và Maintainability**, vì đây là các yếu tố trực tiếp quyết định khả năng vận hành hệ thống khi số lượng khách hàng và tài xế tăng cao.


