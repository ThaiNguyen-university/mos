
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
        <form id="theForm" action="https://script.google.com/macros/s/AKfycbwhTnX8CTNxzxXTget1YY4GimAiY9vMsoGaL0wfTtQ7yGP7O0m09eTpwvxOQMM0hCpKfA/exec" method="GET" onsubmit="return preventRepeatedSubmission();">
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
            <div class="card-header">Câu 1</div>
            <div class="card-body">
                <p>
                    <audio controls preload="none" src="wavs/2.pretrained_english_lien_200cau/pretrained_english_lien_200cau_14_checkpoint_2500_waveglow_synthesis.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q1" id="q1_1" value="5" required>
                    <label class="form-check-label" for="q1_1">５（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q1" id="q1_2" value="4" required>
                    <label class="form-check-label" for="q1_2">４（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q1" id="q1_3" value="3" required>
                    <label class="form-check-label" for="q1_3">３（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q1" id="q1_4" value="2" required>
                    <label class="form-check-label" for="q1_4">２（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q1" id="q1_5" value="1" required>
                    <label class="form-check-label" for="q1_5">１（Tệ）</label>
                </div>
            </div>
        </div>


        <div class="card form-group">
            <div class="card-header">Câu 2</div>
            <div class="card-body">
                <p>
                    <audio controls preload="none" src="wavs/1.from_scatch_lien_200cau/from_scatch_lien_200_cau_9_checkpoint_2900_waveglow_synthesis.wav
">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q2" id="q2_1" value="5" required>
                    <label class="form-check-label" for="q2_1">５（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q2" id="q2_2" value="4" required>
                    <label class="form-check-label" for="q2_2">４（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q2" id="q2_3" value="3" required>
                    <label class="form-check-label" for="q2_3">３（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q2" id="q2_4" value="2" required>
                    <label class="form-check-label" for="q2_4">２（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q2" id="q2_5" value="1" required>
                    <label class="form-check-label" for="q2_5">１（Tệ）</label>
                </div>
            </div>
        </div>

<div class="card form-group">
            <div class="card-header">Câu 3</div>
            <div class="card-body">
                <p>
                    <audio controls preload="none" src="wavs/1.from_scatch_lien_200cau/from_scatch_lien_200_cau_9_checkpoint_2900_waveglow_synthesis.wav
">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q3" id="q3_1" value="5" required>
                    <label class="form-check-label" for="q3_1">５（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q3" id="q3_2" value="4" required>
                    <label class="form-check-label" for="q3_2">４（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q3" id="q3_3" value="3" required>
                    <label class="form-check-label" for="q3_3">３（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q3" id="q3_4" value="2" required>
                    <label class="form-check-label" for="q3_4">２（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q3" id="q3_5" value="1" required>
                    <label class="form-check-label" for="q3_5">１（Tệ）</label>
                </div>
            </div>
        </div>
        
        <div class="card form-group">
            <div class="card-header">Câu 4</div>
            <div class="card-body">
                <p>
                    <audio controls preload="none" src="wavs/1.from_scatch_lien_200cau/from_scatch_lien_200_cau_9_checkpoint_2900_waveglow_synthesis.wav
">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q4" id="q4_1" value="5" required>
                    <label class="form-check-label" for="q4_1">５（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q4" id="q4_2" value="4" required>
                    <label class="form-check-label" for="q4_2">４（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q4" id="q4_3" value="3" required>
                    <label class="form-check-label" for="q4_3">３（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q4" id="q4_4" value="2" required>
                    <label class="form-check-label" for="q4_4">２（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q4" id="q4_5" value="1" required>
                    <label class="form-check-label" for="q4_5">１（Tệ）</label>
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
