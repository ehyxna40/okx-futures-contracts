# giao dịch futures OKX: Hướng dẫn chọn hợp đồng, tính phí và vào lệnh có kiểm soát cho người mới

Tìm kiếm “giao dịch futures OKX” thường không chỉ có nghĩa là muốn biết nút Buy và Sell nằm ở đâu. Phần lớn người mới đang cần câu trả lời thực tế hơn: futures là gì, nên bắt đầu với loại hợp đồng nào, phí được tính ra sao, dùng đòn bẩy bao nhiêu, khác nhau giữa ký quỹ chéo và ký quỹ cô lập thế nào, và làm sao tránh bị thanh lý chỉ vì một biến động giá ngắn.

OKX hiện hỗ trợ nhiều loại hợp đồng futures, trong đó phổ biến nhất là **futures vĩnh cửu ký quỹ bằng USDT**, **futures vĩnh cửu ký quỹ bằng crypto** và một số hợp đồng kỳ hạn hoặc sản phẩm phái sinh khác tùy khu vực. Hợp đồng vĩnh cửu không có ngày đáo hạn cố định, nhưng có cơ chế funding để giúp giá hợp đồng bám sát giá spot.

Bài viết này đi theo đúng quy trình mà một người mới cần: hiểu sản phẩm, chọn chế độ ký quỹ, kiểm tra phí, thực hành bằng tài khoản demo rồi mới cân nhắc giao dịch bằng tiền thật.

> **Lưu ý:** Giao dịch futures sử dụng đòn bẩy có thể khiến khoản lỗ tăng nhanh và dẫn đến thanh lý vị thế. Sản phẩm, giới hạn đòn bẩy, phương thức nạp tiền và khả năng sử dụng có thể khác nhau tùy quốc gia hoặc khu vực. Hãy kiểm tra thông tin hiển thị trong tài khoản OKX của bạn trước khi giao dịch.

## Futures OKX là gì?

Futures là sản phẩm phái sinh theo dõi biến động giá của một tài sản cơ sở như BTC, ETH hoặc SOL. Khi giao dịch futures, bạn không nhất thiết phải mua và nắm giữ đồng coin đó như giao dịch spot. Thay vào đó, bạn mở một vị thế dựa trên dự đoán giá sẽ tăng hoặc giảm.

Có hai hướng lệnh cơ bản:

- **Mua / Long:** kỳ vọng giá tăng.
- **Bán / Short:** kỳ vọng giá giảm.

Ví dụ, nếu bạn mở vị thế Long BTCUSDT và giá BTC tăng, vị thế có thể có lãi trước khi trừ phí. Nếu BTC giảm theo hướng ngược lại, vị thế bị lỗ. Với vị thế Short, logic đảo ngược: giá giảm có thể tạo lợi nhuận, còn giá tăng gây thua lỗ.

Điểm khiến futures khác spot nằm ở **đòn bẩy**. Bạn có thể dùng một lượng ký quỹ nhỏ hơn giá trị danh nghĩa của vị thế. Đòn bẩy giúp tăng mức tiếp xúc với thị trường, nhưng cũng làm cho biến động nhỏ của giá ảnh hưởng lớn hơn đến phần vốn ký quỹ.

Nói đơn giản: đòn bẩy không biến một giao dịch xấu thành giao dịch tốt. Nó chỉ khiến kết quả đến nhanh hơn.

## Các loại futures phổ biến trên OKX

### Futures vĩnh cửu ký quỹ bằng USDT

Đây thường là lựa chọn dễ hiểu nhất với người mới. Bạn dùng USDT làm tài sản ký quỹ và thanh toán lãi lỗ. Ví dụ phổ biến là BTCUSDT Perpetual.

Ưu điểm chính:

- Dễ theo dõi vì giá trị và lãi lỗ được tính bằng USDT.
- Không cần dùng BTC làm tài sản thanh toán.
- Phù hợp với chiến lược Long hoặc Short ngắn hạn.
- Không có ngày hết hạn cố định.

Bạn vẫn phải theo dõi funding. Khi funding dương, bên Long thường trả funding cho bên Short. Khi funding âm, bên Short thường trả cho bên Long. Khoản này được trao đổi trực tiếp giữa những người đang giữ hai phía của hợp đồng, không phải phí dịch vụ do OKX thu riêng.

### Futures vĩnh cửu ký quỹ bằng crypto

Với loại này, tài sản cơ sở như BTC có thể được dùng làm tài sản ký quỹ hoặc tài sản thanh toán tùy hợp đồng. Cách tính lãi lỗ và phí phức tạp hơn vì giá trị cuối cùng không chỉ phụ thuộc vào biến động hợp đồng mà còn liên quan đến giá của tài sản ký quỹ.

Loại hợp đồng này phù hợp hơn với người đã hiểu:

- Giá trị danh nghĩa của hợp đồng.
- Cách tính phí theo coin.
- Rủi ro khi giá tài sản ký quỹ biến động.
- Khác biệt giữa giá đánh dấu và giá khớp lệnh.

Nếu bạn mới tìm hiểu giao dịch futures OKX, USDT-margined thường dễ theo dõi hơn crypto-margined.

### Futures kỳ hạn

Futures kỳ hạn có ngày đáo hạn hoặc thời điểm thanh toán cụ thể. Khác với hợp đồng vĩnh cửu, bạn cần chú ý đến ngày hết hạn, giá thanh toán và phí settlement nếu có.

Không nên chọn futures kỳ hạn chỉ vì thấy đòn bẩy hoặc mức phí hiển thị thấp hơn. Cấu trúc sản phẩm khác nhau, và việc giữ vị thế đến gần ngày đáo hạn có thể tạo ra các khoản phí hoặc rủi ro mà người mới chưa quen.

### Các hợp đồng khác

OKX cũng hiển thị những sản phẩm phái sinh khác tùy khu vực, bao gồm một số hợp đồng liên quan đến hàng hóa hoặc tài sản ngoài crypto. Trang giao dịch có thể hiển thị các hợp đồng như vàng, bạc, dầu hoặc khí tự nhiên ở một số thị trường được hỗ trợ. Tuy nhiên, sản phẩm khả dụng không giống nhau giữa mọi quốc gia.

Trước khi lập kế hoạch giao dịch, hãy kiểm tra trực tiếp danh sách sản phẩm trong tài khoản của bạn. Không nên dựa vào một ảnh chụp màn hình hoặc video cũ để kết luận rằng một hợp đồng chắc chắn vẫn được hỗ trợ.

## Các nhóm sản phẩm và chi phí futures trên OKX

OKX không bán futures theo kiểu gói Basic, Pro hoặc Premium cố định. Chi phí phụ thuộc vào loại công cụ, cặp giao dịch, cấp phí của tài khoản và việc lệnh được khớp dưới dạng maker hay taker.

Bảng dưới đây bao quát các nhóm futures thường được hiển thị trong hệ thống OKX. Các tỷ lệ chính xác cần kiểm tra trong bảng phí của tài khoản vì OKX có thể điều chỉnh theo khu vực, cặp giao dịch và cấp VIP.

| Nhóm sản phẩm | Tài sản ký quỹ / thanh toán | Đặc điểm chính | Chi phí cần kiểm tra | Mua hoặc mở tài khoản |
| --- | --- | --- | --- | --- |
| Futures vĩnh cửu ký quỹ USDT | USDT | Không có ngày hết hạn; phổ biến với BTCUSDT, ETHUSDT và nhiều cặp khác | Phí maker, taker và funding | [ Đăng ký OKX với mã CASH20](https://okx.com/join/CASH20) |
| Futures vĩnh cửu ký quỹ USDC hoặc USD | USDC, USD hoặc tài sản được hỗ trợ tùy khu vực | Thanh toán theo loại tiền định giá của hợp đồng | Phí giao dịch, funding và điều kiện khu vực | [ Kiểm tra quyền truy cập futures OKX](https://okx.com/join/CASH20) |
| Futures vĩnh cửu ký quỹ bằng crypto | BTC hoặc tài sản crypto của hợp đồng | Có thể dùng tài sản cơ sở làm tài sản thanh toán; cách tính phức tạp hơn | Phí maker, taker, funding và biến động tài sản ký quỹ | [ Xem các hợp đồng futures khả dụng](https://okx.com/join/CASH20) |
| Futures kỳ hạn | Crypto hoặc stablecoin tùy hợp đồng | Có ngày đáo hạn hoặc thời điểm thanh toán | Phí giao dịch và phí settlement nếu áp dụng | [ Mở tài khoản để xem sản phẩm](https://okx.com/join/CASH20) |
| Hợp đồng futures hàng hóa hoặc sản phẩm đặc thù | Tùy sản phẩm và khu vực | Chỉ khả dụng ở một số thị trường | Phí riêng, giới hạn và điều kiện sản phẩm | [ Kiểm tra danh sách sản phẩm trong tài khoản](https://okx.com/join/CASH20) |

OKX cho biết mức phí hiện tại của từng tài khoản được hiển thị sau khi đăng nhập. Bạn có thể xem cấp phí, khối lượng giao dịch futures trong 30 ngày và mức phí áp dụng cho từng công cụ trong khu vực phí giao dịch. Mức phí hiển thị khi chưa đăng nhập có thể khác với mức áp dụng cho tài khoản của bạn.

Thông tin hoàn phí **20% với mã CASH20** được cung cấp kèm liên kết đăng ký trong đề bài. Điều kiện, phạm vi áp dụng và cách tính hoàn phí có thể phụ thuộc vào chương trình affiliate hoặc khu vực tài khoản, vì vậy hãy kiểm tra nội dung hiển thị sau khi mở liên kết và trước khi nạp tiền.

## Phí giao dịch futures được tính như thế nào?

### Phí maker và taker

Lệnh **taker** là lệnh khớp ngay với lệnh đang có trong sổ lệnh. Lệnh thị trường thường rơi vào nhóm này, nhưng một lệnh giới hạn cũng có thể bị tính như taker nếu được khớp ngay lập tức.

Lệnh **maker** là lệnh được đưa vào sổ lệnh và chờ một đối tác khớp. Maker thường có mức phí thấp hơn taker, nhưng không phải mọi lệnh giới hạn đều mặc nhiên là maker. Cách lệnh thực sự được khớp mới quyết định loại phí.

Với futures ký quỹ bằng USDT hoặc USDC, công thức cơ bản là:

text
Phí giao dịch = Tỷ lệ phí × Số hợp đồng × Hệ số nhân × Quy mô hợp đồng × Giá khớp


Ví dụ minh họa của OKX dùng một hợp đồng BTCUSDT có quy mô 0,01 BTC. Với 100 hợp đồng, giá BTC là 20.000 USDT và phí taker là 0,05%, giá trị danh nghĩa là:

text
100 × 0,01 × 20.000 = 20.000 USDT


Phí giao dịch cho một lần khớp sẽ là:

text
20.000 × 0,05% = 10 USDT


Đây chỉ là ví dụ để hiểu công thức. Tỷ lệ thực tế của bạn có thể khác theo cấp phí, cặp giao dịch và khu vực.

### Funding không giống phí giao dịch

Funding thường bị hiểu nhầm là lãi vay. Trên OKX, funding của hợp đồng vĩnh cửu là khoản trao đổi giữa bên Long và bên Short để hỗ trợ việc giữ giá hợp đồng gần giá spot. Khi funding dương, Long thường trả cho Short; khi funding âm, Short thường trả cho Long.

Công thức tổng quát:

text
Phí funding = Giá trị vị thế × Lãi suất funding


Funding không nhất thiết được tính cùng một khoảng thời gian cho mọi hợp đồng. Nhiều hợp đồng sử dụng chu kỳ 8 giờ, trong khi một số hợp đồng có thể dùng chu kỳ 1, 2 hoặc 4 giờ. Khoảng thời gian cụ thể được hiển thị trên trang giao dịch của hợp đồng đó.

Trước khi giữ một vị thế qua nhiều giờ, hãy xem ba thông tin:

1. Funding hiện tại là dương hay âm.
2. Ai sẽ trả funding ở kỳ tiếp theo.
3. Thời gian còn lại đến lần thanh toán kế tiếp.

### Phí thanh lý và phí settlement

Nếu vị thế bị thanh lý cưỡng chế, phí có thể được tính theo mức taker của cấp phí hiện tại. Futures kỳ hạn có thể có phí settlement; tài liệu phí của OKX nêu mức phí settlement hết hạn là 0,01% cho futures kỳ hạn trong trường hợp áp dụng.

Vì vậy, khi ước tính chi phí, đừng chỉ nhìn vào phí mở lệnh. Một vị thế futures có thể phát sinh:

- Phí mở vị thế.
- Phí đóng vị thế.
- Funding.
- Phí thanh lý nếu bị cưỡng chế.
- Phí settlement đối với một số hợp đồng kỳ hạn.
- Chi phí nạp, rút hoặc chuyển đổi do phương thức thanh toán áp dụng.

## Hướng dẫn giao dịch futures OKX từng bước

### Bước 1: Mở tài khoản và hoàn tất xác minh

Truy cập liên kết đăng ký có mã **CASH20**, tạo tài khoản và hoàn tất các bước xác minh được yêu cầu. Việc xác minh không đảm bảo mọi sản phẩm futures đều khả dụng tại khu vực của bạn; hệ thống sẽ quyết định dựa trên quốc gia cư trú, loại tài khoản và quy định áp dụng.

[👉 Đăng ký OKX và kiểm tra ưu đãi CASH20](https://okx.com/join/CASH20)

### Bước 2: Chuyển tài sản vào tài khoản giao dịch

OKX tách tài khoản Funding và tài khoản Trading trong quy trình quản lý tài sản. Sau khi nạp tiền, bạn cần dùng chức năng chuyển tiền để đưa tài sản từ Funding sang Trading trước khi mở vị thế futures.

Đừng chuyển toàn bộ số dư vào futures ngay từ đầu. Một cách thận trọng hơn là chỉ chuyển số tiền bạn đã xác định có thể dùng cho việc học và kiểm tra hệ thống.

### Bước 3: Chọn hợp đồng

Vào khu vực **Trade > Futures**, sau đó chọn loại sản phẩm:

- Perpetual hoặc futures kỳ hạn.
- USDT-margined, crypto-margined hoặc loại tiền ký quỹ khác.
- Cặp giao dịch như BTCUSDT Perpetual hoặc ETHUSDT Perpetual.

Với người mới, hãy ưu tiên một cặp có thanh khoản tốt và thông tin dễ theo dõi. Không nên bắt đầu bằng một token ít thanh khoản chỉ vì mức biến động nhìn có vẻ hấp dẫn.

### Bước 4: Chọn ký quỹ cô lập hoặc ký quỹ chéo

**Ký quỹ cô lập** giới hạn phần tiền được phân bổ cho vị thế. Nếu vị thế bị thanh lý, số tiền chịu rủi ro được giới hạn trong phần ký quỹ của vị thế đó, dù vẫn có thể mất toàn bộ khoản ký quỹ đã phân bổ.

**Ký quỹ chéo** dùng số dư phù hợp trong tài khoản làm tài sản hỗ trợ cho vị thế. Cách này có thể giúp vị thế có thêm khoảng chịu biến động, nhưng đồng thời mở rộng phạm vi tài sản có thể bị ảnh hưởng nếu giao dịch đi ngược kỳ vọng.

OKX cũng có các chế độ tài khoản như đơn tệ, đa tệ và danh mục đầu tư. Cách tài sản được tính làm ký quỹ có thể khác giữa các chế độ.

Nếu chưa hiểu rõ cách tài sản được dùng làm ký quỹ, nên bắt đầu bằng ký quỹ cô lập và đòn bẩy thấp hơn.

### Bước 5: Chọn đòn bẩy

Đòn bẩy 10x không có nghĩa là bạn chỉ có thể lỗ 10% rồi dừng lại. Giá thanh lý còn phụ thuộc vào giá vào lệnh, loại ký quỹ, quy mô vị thế, phí, funding, mức duy trì ký quỹ và điều kiện của hợp đồng.

Các lỗi thường gặp khi chọn đòn bẩy:

- Chọn mức tối đa vì nghĩ đó là mức “nên dùng”.
- Dùng toàn bộ số dư làm ký quỹ.
- Mở vị thế quá lớn so với số vốn.
- Không đặt mức cắt lỗ.
- Bỏ qua giá thanh lý hiển thị trên bảng lệnh.

Đòn bẩy thấp không loại bỏ rủi ro, nhưng thường cho bạn nhiều thời gian hơn để xử lý khi thị trường đi ngược.

### Bước 6: Chọn loại lệnh

Một số loại lệnh thường gặp:

- **Market:** ưu tiên khớp nhanh, nhưng chịu rủi ro trượt giá và thường bị tính phí taker.
- **Limit:** đặt giá cụ thể; có thể trở thành maker nếu không khớp ngay.
- **Trigger:** chỉ kích hoạt khi giá đạt điều kiện đã đặt.
- **TP/SL:** dùng để chốt lời hoặc dừng lỗ theo điều kiện định trước.

OKX cho phép thiết lập Take Profit và Stop Loss trước khi gửi lệnh futures. Khi đóng vị thế bằng lệnh thị trường trong biến động mạnh, phí taker và mức trượt giá có thể cao hơn so với lệnh giới hạn.

### Bước 7: Kiểm tra trước khi xác nhận

Trước khi bấm mở vị thế, kiểm tra:

- Cặp giao dịch.
- Hướng Long hoặc Short.
- Chế độ ký quỹ.
- Mức đòn bẩy.
- Số lượng hợp đồng.
- Giá vào lệnh.
- Giá thanh lý ước tính.
- Funding hiện tại.
- Phí maker và taker.
- Mức ký quỹ khả dụng.

Một thao tác kiểm tra kéo dài vài giây có thể tránh được lỗi chọn nhầm cặp hoặc mở nhầm hướng. Trong futures, những lỗi nhỏ thường không có thời gian để sửa từ tốn.

## Cách thực hành giao dịch futures OKX bằng tài khoản demo

OKX cung cấp giao dịch demo trên web và ứng dụng. Người mới có thể chọn khu vực Demo trading, chọn Perpetual, loại ký quỹ USDT, sau đó thử mở Long hoặc Short bằng số dư ảo.

Tài khoản demo nên được dùng để kiểm tra quy trình, không phải để chứng minh rằng một chiến lược chắc chắn có lãi. Bạn có thể thực hành:

1. Chuyển sang cặp BTCUSDT Perpetual.
2. Chọn ký quỹ cô lập.
3. Dùng mức đòn bẩy thấp.
4. Đặt một lệnh giới hạn nhỏ.
5. Thêm TP/SL.
6. Theo dõi funding và giá thanh lý.
7. Đóng vị thế thủ công.
8. Xem lịch sử lệnh và khoản phí mô phỏng.

Nếu không biết mình đang ở chế độ demo hay giao dịch thật, hãy dừng lại và kiểm tra giao diện trước khi xác nhận lệnh. OKX có nút chuyển giữa giao dịch demo và giao dịch thật, vì vậy việc đọc đúng nhãn trên màn hình là bắt buộc.

## Những lỗi khiến người mới dễ bị thanh lý

### Dùng đòn bẩy để “gỡ lỗ”

Sau một lệnh thua, nhiều người tăng đòn bẩy hoặc tăng khối lượng để lấy lại tiền nhanh hơn. Đây là cách biến một khoản lỗ có giới hạn thành một chuỗi lệnh ngày càng khó kiểm soát.

### Nhầm giá trị vị thế với số tiền ký quỹ

Một vị thế trị giá 10.000 USDT không có nghĩa bạn chỉ đang giao dịch 10.000 USDT. Nếu dùng đòn bẩy, số tiền ký quỹ có thể nhỏ hơn nhiều, nhưng lãi lỗ vẫn được tính trên giá trị vị thế.

### Bỏ qua funding

Một vị thế giữ lâu có thể chịu nhiều lần thanh toán funding. Nếu funding đang bất lợi và giá không di chuyển đủ để bù chi phí, kết quả cuối cùng có thể kém hơn dự tính.

### Dùng ký quỹ chéo mà không hiểu phạm vi rủi ro

Ký quỹ chéo có thể sử dụng nhiều tài sản hơn để duy trì vị thế. Điều này không đồng nghĩa với việc giao dịch an toàn hơn. Nó có thể khiến nhiều tài sản trong tài khoản cùng bị ảnh hưởng khi vị thế xấu đi.

### Không đặt kế hoạch thoát lệnh

Trước khi vào lệnh, hãy xác định:

- Mức giá sai nhận định.
- Mức lỗ tối đa chấp nhận.
- Điều kiện chốt lời.
- Khi nào không nên tiếp tục trung bình giá.
- Vị thế sẽ được đóng thủ công hay bằng TP/SL.

Không có kế hoạch thoát lệnh, nút “đóng vị thế” thường chỉ được sử dụng sau khi cảm xúc đã quyết định thay cho bạn.

## Giao dịch futures OKX có phù hợp với ai?

Futures có thể phù hợp với người:

- Đã hiểu sự khác nhau giữa spot và phái sinh.
- Biết cách đọc giá thanh lý và mức ký quỹ.
- Chấp nhận khả năng mất nhanh một phần hoặc toàn bộ khoản ký quỹ.
- Có quy tắc quản lý rủi ro rõ ràng.
- Muốn phòng hộ vị thế spot hoặc giao dịch hai chiều khi thị trường tăng giảm.

Futures không phù hợp với người chỉ muốn mua và giữ crypto đơn giản, chưa hiểu funding hoặc đang tìm cách kiếm lợi nhuận chắc chắn trong thời gian ngắn.

Nếu mục tiêu chính là học cách sử dụng giao diện, tài khoản demo là điểm bắt đầu hợp lý hơn. Nếu mục tiêu là giảm phí, hãy đăng nhập và xem mức maker/taker thực tế của tài khoản thay vì lấy một con số trên bài viết cũ. OKX hiển thị phí theo từng công cụ và cặp giao dịch, nên phí spot và phí futures không nhất thiết giống nhau.

## Kết luận

Giao dịch futures OKX gồm nhiều lớp quyết định: chọn loại hợp đồng, chọn tài sản ký quỹ, chọn chế độ margin, kiểm tra funding, ước tính phí và xác định điểm thoát. Nút mở Long hoặc Short chỉ là phần dễ nhìn thấy nhất.

Với người mới, quy trình thực tế nên là:

1. Đọc thông tin của hợp đồng muốn giao dịch.
2. Dùng tài khoản demo để làm quen.
3. Bắt đầu với ký quỹ cô lập và quy mô nhỏ.
4. Kiểm tra phí maker, taker và funding trước khi vào lệnh.
5. Đặt TP/SL trước hoặc ngay khi mở vị thế.
6. Không sử dụng số tiền cần cho sinh hoạt hoặc nghĩa vụ tài chính.
7. Kiểm tra điều kiện sản phẩm tại khu vực cư trú.

Bạn có thể bắt đầu từ liên kết OKX có mã **CASH20** để xem chương trình hoàn phí được áp dụng như thế nào trong tài khoản của mình:

[👉 Mở tài khoản OKX với mã CASH20 và kiểm tra ưu đãi](https://okx.com/join/CASH20)
