Hướng dẫn sơ bộ về phần mền của mình!

- Chú ý nhá: File sau khi dịch xong nó sẽ bị thay đổi hơi nhiều ví dụ như có rất ngoặc kép (""), mình có test qua thì nó không ảnh hương đến game nên mình để nguyên, nếu các bạn thấy nó bị lỗi thì liên hệ
với mình nhé, vì mình cx chưa test dc nhiều game nên cx k rõ nó có bị lỗi hay không 

- Có 3 lựa chọn cho việc dịch thuật nó nằm ở phần "Loại", trừ "cơ bạn" ra các bạn phải thêm địa chỉ file text của các bạn vào sau đó input, phần mên sẽ tự nhận diện là loại mấy
	Cơ bản: Là loại dùng để dịch cơ bản như GGTranslate
	Loại 1: Sử dụng để dịch các tệp có dạng ntn:
		{
			"Id": 10017,
			"KeyName": "Mr.Wang",
			"Message": "(Sure enough, it is the \"mouse\" problem, and let me operate it)　",
			"LanguageId": 0,
			"Queue": 5,
			"EventID": 1005,
			"PassID": 1001,
			"SoundID": 0,
			"LoopSound": 0
		},
	Loại 2: Sử dụng để dịch các tệp có dạng ntn:
		"OK","OK";
		"Public Universes","Public Universes";
		"Colony Defense","Colony Defense";
		"Private Universe","Private Universe";
		"Pair Mobile App","Pair Mobile App";
- Các loại text dịch nó có cấc điều kiện khác nhau, 
	+ Đối với loại "cơ bản", bạn chỉ cần nhập từ hay một văn bản cần dịch, sau dó chỉnh ngôn ngữ cần dịch -> ngôn ngữ cần dịch dưới chữ Transale, sau đó bấm Translate và đợi
	+ Với "Loại 1", chúng ta cần có điều kiện và file text để dịch. Ví dụ như file này:
			{
				"Id": 10017,
				"KeyName": "Mr.Wang",
				"Message": "(Sure enough, it is the \"mouse\" problem, and let me operate it)　",
				"LanguageId": 0,
				"Queue": 5,
				"EventID": 1005,
				"PassID": 1001,
				"SoundID": 0,
				"LoopSound": 0
			},
		điều kiện bạn có thể lấy "	"Message": " hoặc "	"KeyName": " hay tương tự như những cái khác (Các bạn cẩn thận trong việc copy, đừng bỏ qua kể cả là khoảng trống, nếu không nó có thể khi dịch xong nó chả ra cái j cả !), nó sẽ trả về cái tương tự nhưng đã được dịch ở dòng bạn chọn.
	+ Đối với "Loại 2", Chúng ta cần chọn cột để dịch. Ví dụ như cái này:
			,次へ,Next,,,
			,キャンセル,Cancel,,,
			,閉じる,Close,,,
			,削除,Delete,,,
			,リセット,Reset,,,
			,保存,Save,,,
			,戻る,Return,,,
		cứ sau 1 dấu phẩy nó sẽ tính là một cột, vậy nên nếu bạn muốn dịch cột tiếng anh thì bạn phải chọn là 2, các cột được tính từ 0 đến ...
- Ở đây, cơ bản nó sẽ dịch hết, cho nên nếu các bạn không muốn nó dịch cái j thì hãy thêm nó vào cột ngoại lệ, nó sẽ ấp dụng hết trên tất cả các loại dịch thuật, ví dụ
mình không muốn dịch từ "mouse" trong câu "(Sure enough, it is the \"mouse\" problem, and let me operate it)　", vậy thì mình sẽ thêm \"mouse\" vào phần "ngoại lệ",
nó sẽ dữ nguyên mà không dịch

- Sau khi dịch xong, các bạn có thể Export file về lại duôi như cũ và có thể chạy game thử, nếu game k nên thì các bạn nên kiểm tra lại file dịch, bởi đôi khi sẽ có sợ cố bất ngờ xẩy ra khi dịch 

- (Khi nào bị Crash thì mới cần để ý thôi !)có để ngoại lệ cho nó rồi nhưng đôi khi phần mền sẽ bị Crash do một vài lỗi ngoại lệ, thường thì sẽ là do ở cuối dòng chữ không phải dấu phẩy (,) vi dụ: (,キャンセル,Cancel,,;) nên nó không đọc được, các bạn phải conver nó
về dạng như thế này (,キャンセル,Cancel,,,) nhé mọi người chú ý cẩn thận nhé, có thể dùng Notpab hay cái j sửa cx được.

- Một số luu ý, do là phần mên phát triên đẻ cho các bạn dịch thuật, và sử dụng google để dịch nên đôi khi sẽ có một vài lỗi nhỏ, nếu sự cố gì trong lúc dùng mong các bạn
liên hệ với mình qua gmail: gauk1101@gmail.com hoặc zexttv@gmail.com.
- Cảm ơn bạn đã sử dụng phần mền của mình
