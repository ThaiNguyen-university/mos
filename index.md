
<!doctype html>
<html>

<head>
    <title> Hình thức thử nghiệm MOS-1</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.1/css/bootstrap.min.css"
        integrity="sha384-VCmXjywReHh4PwowAiWNagnWcLhlEJLA5buUprzK8rxFgeH0kww/aWY76TfkUoSX" crossorigin="anonymous">
</head>

<body>
    <div class="jumbotron jumbotron-fluid">
        <div class="container">

    <h1 class="display-4">Thí nghiệm MOS </h1>
    <p class="lead">Đánh giá chất lượng tiếng nói tổng hợp </p>
    <hr class="my-4">
    <p>
        Cảm ơn bạn đã tham gia thử nghiệm này ！
    </p>
    <p>
        Trong thí nghiệm này, chúng tôi sử dụng máy tính để tổng hợp tạo ra giọng nói của con người.
         Các tệp âm thanh sau đây chứa các bản ghi âm thực và các giọng nói tổng hợp, và mỗi câu được kèm theo một bản ghi (120 câu được đảo thứ tự).
         Khách mời được yêu cầu sử dụng tai nghe để nghe và cho điểm sau tùy theo chất lượng của từng tệp âm thanh:
        <ul>
            <li>５: Rất tốt      (Rất tự nhiên, như con người）</li>
            <li>４: Tốt          (Tự nhiên）</li>
            <li>３: Bình thường  (Khá tự nhiên）</li>
            <li>２: Không tốt    (Không tự nhiên）</li>
            <li>１: Rất tệ       (Rất không tự nhiên）</li>
            
            
            
            
        </ul>
    <h3> <strong><u> Lưu ý:</u> Khuyến cáo sử dụng trình duyệt Firefox trên máy tính hoặc smartphone. </strong> </h3>
            </p>

        </div>
    </div>

    <div class="container" id="form_container">
        <form id="theForm" action="https://script.google.com/macros/s/AKfycbzFs2V5zHDZvmrIlW3CLYwwSunZD4mgbPqreIqWohZ8Zrw5BH9KqjS6ckpApFoHvDlUcA/exec" method="GET" onsubmit="return preventRepeatedSubmission();">
            <div class="form-group">
                <label for="name">Tên ：</label>
                <input class="form-control" type="text" inputmode="text" name="name" required>
                <small class="form-text text-muted">Cần thiết*</small>
            </div>
            <div class="form-group">
                <label for="mail">E-mail：</label>
                <input class="form-control" type="text" inputmode="email" placeholder="account@example.com" name="mail">
                <small class="form-text text-muted">Nếu bạn thắng, chúng tôi sẽ thông báo cho bạn qua email</small>
            </div>


        <div class="card form-group">
            <div class="card-header">Câu 75</div>
            <div class="card-body">
                <p>
                    <audio controls preload="none" src="wavs/2.pretrained_english_lien_200cau/pretrained_english_lien_200cau_14_checkpoint_2500_waveglow_synthesis.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q75" id="q75_1" value="5" required>
                    <label class="form-check-label" for="q75_1">５（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q75" id="q75_2" value="4" required>
                    <label class="form-check-label" for="q75_2">４（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q75" id="q75_3" value="3" required>
                    <label class="form-check-label" for="q75_3">３（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q75" id="q75_4" value="2" required>
                    <label class="form-check-label" for="q75_4">２（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q75" id="q75_5" value="1" required>
                    <label class="form-check-label" for="q75_5">１（Tệ）</label>
                </div>
            </div>
        </div>


        <div class="card form-group">
            <div class="card-header">Câu 25</div>
            <div class="card-body">
                <p>
                    <audio controls preload="none" src="wavs/1.from_scatch_lien_200cau/from_scatch_lien_200_cau_9_checkpoint_2900_waveglow_synthesis.wav
">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q25" id="q25_1" value="5" required>
                    <label class="form-check-label" for="q25_1">５（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q25" id="q25_2" value="4" required>
                    <label class="form-check-label" for="q25_2">４（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q25" id="q25_3" value="3" required>
                    <label class="form-check-label" for="q25_3">３（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q25" id="q25_4" value="2" required>
                    <label class="form-check-label" for="q25_4">２（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q25" id="q25_5" value="1" required>
                    <label class="form-check-label" for="q25_5">１（Tệ）</label>
                </div>
            </div>
        </div>


        

</div>
            <input type="text" name="formid" value="1" hidden>
            <input type="text" name="thank" value="Cảm ơn bạn một lần nữa vì đã tham gia thử nghiệm này！" hidden>
            <input class="btn btn-info btn-lg" type="submit" value="Gửi kết quả" id="submitBtn">
            <p class="text-muted">
                <small>Nếu bạn thấy không trả được khi nộp kết quả vui lòng kiểm tra lại xem bạn đã điền tên mình chưa và đã trả lời được mọi câu hỏi chưa, xin cảm ơn。</small>
            </p>
        </form>
    </div>

    <div class="container" style="padding-top: 60px;">
        <p class="text-center text-muted">&copy; Phòng Thí nghiệm tiếng nói</p>
    </div>

    <script type="text/javascript">
        function preventRepeatedSubmission() {
            document.getElementById('submitBtn').disabled = true;
            setTimeout("submitBtn.disabled=false;", 5000);
            return true;
        };
    </script>
</body>

</html>
