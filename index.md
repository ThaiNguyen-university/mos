
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
            <div class="card-header">Câu 118</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/gt15/lien-104-0022.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q118" id="q118_1" value="5" required>
                    <label class="form-check-label" for="q118_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q118" id="q118_2" value="4" required>
                    <label class="form-check-label" for="q118_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q118" id="q118_3" value="3" required>
                    <label class="form-check-label" for="q118_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q118" id="q118_4" value="2" required>
                    <label class="form-check-label" for="q118_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q118" id="q118_5" value="1" required>
                    <label class="form-check-label" for="q118_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 55</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/16m15/16m15_(10).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q55" id="q55_1" value="5" required>
                    <label class="form-check-label" for="q55_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q55" id="q55_2" value="4" required>
                    <label class="form-check-label" for="q55_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q55" id="q55_3" value="3" required>
                    <label class="form-check-label" for="q55_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q55" id="q55_4" value="2" required>
                    <label class="form-check-label" for="q55_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q55" id="q55_5" value="1" required>
                    <label class="form-check-label" for="q55_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 119</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/gt15/lien-106-0001.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q119" id="q119_1" value="5" required>
                    <label class="form-check-label" for="q119_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q119" id="q119_2" value="4" required>
                    <label class="form-check-label" for="q119_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q119" id="q119_3" value="3" required>
                    <label class="form-check-label" for="q119_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q119" id="q119_4" value="2" required>
                    <label class="form-check-label" for="q119_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q119" id="q119_5" value="1" required>
                    <label class="form-check-label" for="q119_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 2</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15/1m15_(2).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q2" id="q2_1" value="5" required>
                    <label class="form-check-label" for="q2_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q2" id="q2_2" value="4" required>
                    <label class="form-check-label" for="q2_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q2" id="q2_3" value="3" required>
                    <label class="form-check-label" for="q2_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q2" id="q2_4" value="2" required>
                    <label class="form-check-label" for="q2_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q2" id="q2_5" value="1" required>
                    <label class="form-check-label" for="q2_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 37</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15/4m15_(7).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q37" id="q37_1" value="5" required>
                    <label class="form-check-label" for="q37_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q37" id="q37_2" value="4" required>
                    <label class="form-check-label" for="q37_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q37" id="q37_3" value="3" required>
                    <label class="form-check-label" for="q37_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q37" id="q37_4" value="2" required>
                    <label class="form-check-label" for="q37_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q37" id="q37_5" value="1" required>
                    <label class="form-check-label" for="q37_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 44</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15/4m15_(14).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q44" id="q44_1" value="5" required>
                    <label class="form-check-label" for="q44_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q44" id="q44_2" value="4" required>
                    <label class="form-check-label" for="q44_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q44" id="q44_3" value="3" required>
                    <label class="form-check-label" for="q44_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q44" id="q44_4" value="2" required>
                    <label class="form-check-label" for="q44_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q44" id="q44_5" value="1" required>
                    <label class="form-check-label" for="q44_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 24</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15/2m15_(9).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q24" id="q24_1" value="5" required>
                    <label class="form-check-label" for="q24_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q24" id="q24_2" value="4" required>
                    <label class="form-check-label" for="q24_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q24" id="q24_3" value="3" required>
                    <label class="form-check-label" for="q24_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q24" id="q24_4" value="2" required>
                    <label class="form-check-label" for="q24_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q24" id="q24_5" value="1" required>
                    <label class="form-check-label" for="q24_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 22</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15/2m15_(7).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q22" id="q22_1" value="5" required>
                    <label class="form-check-label" for="q22_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q22" id="q22_2" value="4" required>
                    <label class="form-check-label" for="q22_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q22" id="q22_3" value="3" required>
                    <label class="form-check-label" for="q22_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q22" id="q22_4" value="2" required>
                    <label class="form-check-label" for="q22_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q22" id="q22_5" value="1" required>
                    <label class="form-check-label" for="q22_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 40</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15/4m15_(10).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q40" id="q40_1" value="5" required>
                    <label class="form-check-label" for="q40_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q40" id="q40_2" value="4" required>
                    <label class="form-check-label" for="q40_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q40" id="q40_3" value="3" required>
                    <label class="form-check-label" for="q40_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q40" id="q40_4" value="2" required>
                    <label class="form-check-label" for="q40_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q40" id="q40_5" value="1" required>
                    <label class="form-check-label" for="q40_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 79</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15a/2m15a_(4).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q79" id="q79_1" value="5" required>
                    <label class="form-check-label" for="q79_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q79" id="q79_2" value="4" required>
                    <label class="form-check-label" for="q79_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q79" id="q79_3" value="3" required>
                    <label class="form-check-label" for="q79_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q79" id="q79_4" value="2" required>
                    <label class="form-check-label" for="q79_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q79" id="q79_5" value="1" required>
                    <label class="form-check-label" for="q79_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 54</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/16m15/16m15_(9).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q54" id="q54_1" value="5" required>
                    <label class="form-check-label" for="q54_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q54" id="q54_2" value="4" required>
                    <label class="form-check-label" for="q54_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q54" id="q54_3" value="3" required>
                    <label class="form-check-label" for="q54_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q54" id="q54_4" value="2" required>
                    <label class="form-check-label" for="q54_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q54" id="q54_5" value="1" required>
                    <label class="form-check-label" for="q54_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 91</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15a/4m15a_(1).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q91" id="q91_1" value="5" required>
                    <label class="form-check-label" for="q91_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q91" id="q91_2" value="4" required>
                    <label class="form-check-label" for="q91_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q91" id="q91_3" value="3" required>
                    <label class="form-check-label" for="q91_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q91" id="q91_4" value="2" required>
                    <label class="form-check-label" for="q91_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q91" id="q91_5" value="1" required>
                    <label class="form-check-label" for="q91_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 10</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15/1m15_(10).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q10" id="q10_1" value="5" required>
                    <label class="form-check-label" for="q10_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q10" id="q10_2" value="4" required>
                    <label class="form-check-label" for="q10_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q10" id="q10_3" value="3" required>
                    <label class="form-check-label" for="q10_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q10" id="q10_4" value="2" required>
                    <label class="form-check-label" for="q10_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q10" id="q10_5" value="1" required>
                    <label class="form-check-label" for="q10_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 56</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/16m15/16m15_(11).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q56" id="q56_1" value="5" required>
                    <label class="form-check-label" for="q56_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q56" id="q56_2" value="4" required>
                    <label class="form-check-label" for="q56_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q56" id="q56_3" value="3" required>
                    <label class="form-check-label" for="q56_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q56" id="q56_4" value="2" required>
                    <label class="form-check-label" for="q56_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q56" id="q56_5" value="1" required>
                    <label class="form-check-label" for="q56_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 39</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15/4m15_(9).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q39" id="q39_1" value="5" required>
                    <label class="form-check-label" for="q39_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q39" id="q39_2" value="4" required>
                    <label class="form-check-label" for="q39_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q39" id="q39_3" value="3" required>
                    <label class="form-check-label" for="q39_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q39" id="q39_4" value="2" required>
                    <label class="form-check-label" for="q39_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q39" id="q39_5" value="1" required>
                    <label class="form-check-label" for="q39_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 102</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15a/4m15a_(12).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q102" id="q102_1" value="5" required>
                    <label class="form-check-label" for="q102_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q102" id="q102_2" value="4" required>
                    <label class="form-check-label" for="q102_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q102" id="q102_3" value="3" required>
                    <label class="form-check-label" for="q102_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q102" id="q102_4" value="2" required>
                    <label class="form-check-label" for="q102_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q102" id="q102_5" value="1" required>
                    <label class="form-check-label" for="q102_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 100</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15a/4m15a_(10).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q100" id="q100_1" value="5" required>
                    <label class="form-check-label" for="q100_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q100" id="q100_2" value="4" required>
                    <label class="form-check-label" for="q100_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q100" id="q100_3" value="3" required>
                    <label class="form-check-label" for="q100_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q100" id="q100_4" value="2" required>
                    <label class="form-check-label" for="q100_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q100" id="q100_5" value="1" required>
                    <label class="form-check-label" for="q100_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 83</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15a/2m15a_(8).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q83" id="q83_1" value="5" required>
                    <label class="form-check-label" for="q83_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q83" id="q83_2" value="4" required>
                    <label class="form-check-label" for="q83_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q83" id="q83_3" value="3" required>
                    <label class="form-check-label" for="q83_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q83" id="q83_4" value="2" required>
                    <label class="form-check-label" for="q83_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q83" id="q83_5" value="1" required>
                    <label class="form-check-label" for="q83_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 46</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/16m15/16m15_(1).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q46" id="q46_1" value="5" required>
                    <label class="form-check-label" for="q46_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q46" id="q46_2" value="4" required>
                    <label class="form-check-label" for="q46_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q46" id="q46_3" value="3" required>
                    <label class="form-check-label" for="q46_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q46" id="q46_4" value="2" required>
                    <label class="form-check-label" for="q46_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q46" id="q46_5" value="1" required>
                    <label class="form-check-label" for="q46_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 72</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15a/1m15a_(12).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q72" id="q72_1" value="5" required>
                    <label class="form-check-label" for="q72_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q72" id="q72_2" value="4" required>
                    <label class="form-check-label" for="q72_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q72" id="q72_3" value="3" required>
                    <label class="form-check-label" for="q72_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q72" id="q72_4" value="2" required>
                    <label class="form-check-label" for="q72_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q72" id="q72_5" value="1" required>
                    <label class="form-check-label" for="q72_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 86</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15a/2m15a_(11).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q86" id="q86_1" value="5" required>
                    <label class="form-check-label" for="q86_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q86" id="q86_2" value="4" required>
                    <label class="form-check-label" for="q86_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q86" id="q86_3" value="3" required>
                    <label class="form-check-label" for="q86_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q86" id="q86_4" value="2" required>
                    <label class="form-check-label" for="q86_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q86" id="q86_5" value="1" required>
                    <label class="form-check-label" for="q86_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 85</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15a/2m15a_(10).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q85" id="q85_1" value="5" required>
                    <label class="form-check-label" for="q85_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q85" id="q85_2" value="4" required>
                    <label class="form-check-label" for="q85_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q85" id="q85_3" value="3" required>
                    <label class="form-check-label" for="q85_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q85" id="q85_4" value="2" required>
                    <label class="form-check-label" for="q85_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q85" id="q85_5" value="1" required>
                    <label class="form-check-label" for="q85_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 60</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/16m15/16m15_(15).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q60" id="q60_1" value="5" required>
                    <label class="form-check-label" for="q60_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q60" id="q60_2" value="4" required>
                    <label class="form-check-label" for="q60_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q60" id="q60_3" value="3" required>
                    <label class="form-check-label" for="q60_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q60" id="q60_4" value="2" required>
                    <label class="form-check-label" for="q60_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q60" id="q60_5" value="1" required>
                    <label class="form-check-label" for="q60_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 108</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/gt15/lien-97-0003.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q108" id="q108_1" value="5" required>
                    <label class="form-check-label" for="q108_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q108" id="q108_2" value="4" required>
                    <label class="form-check-label" for="q108_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q108" id="q108_3" value="3" required>
                    <label class="form-check-label" for="q108_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q108" id="q108_4" value="2" required>
                    <label class="form-check-label" for="q108_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q108" id="q108_5" value="1" required>
                    <label class="form-check-label" for="q108_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 67</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15a/1m15a_(7).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q67" id="q67_1" value="5" required>
                    <label class="form-check-label" for="q67_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q67" id="q67_2" value="4" required>
                    <label class="form-check-label" for="q67_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q67" id="q67_3" value="3" required>
                    <label class="form-check-label" for="q67_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q67" id="q67_4" value="2" required>
                    <label class="form-check-label" for="q67_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q67" id="q67_5" value="1" required>
                    <label class="form-check-label" for="q67_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 76</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15a/2m15a_(1).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q76" id="q76_1" value="5" required>
                    <label class="form-check-label" for="q76_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q76" id="q76_2" value="4" required>
                    <label class="form-check-label" for="q76_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q76" id="q76_3" value="3" required>
                    <label class="form-check-label" for="q76_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q76" id="q76_4" value="2" required>
                    <label class="form-check-label" for="q76_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q76" id="q76_5" value="1" required>
                    <label class="form-check-label" for="q76_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 41</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15/4m15_(11).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q41" id="q41_1" value="5" required>
                    <label class="form-check-label" for="q41_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q41" id="q41_2" value="4" required>
                    <label class="form-check-label" for="q41_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q41" id="q41_3" value="3" required>
                    <label class="form-check-label" for="q41_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q41" id="q41_4" value="2" required>
                    <label class="form-check-label" for="q41_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q41" id="q41_5" value="1" required>
                    <label class="form-check-label" for="q41_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 29</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15/2m15_(14).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q29" id="q29_1" value="5" required>
                    <label class="form-check-label" for="q29_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q29" id="q29_2" value="4" required>
                    <label class="form-check-label" for="q29_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q29" id="q29_3" value="3" required>
                    <label class="form-check-label" for="q29_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q29" id="q29_4" value="2" required>
                    <label class="form-check-label" for="q29_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q29" id="q29_5" value="1" required>
                    <label class="form-check-label" for="q29_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 117</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/gt15/lien-104-0021.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q117" id="q117_1" value="5" required>
                    <label class="form-check-label" for="q117_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q117" id="q117_2" value="4" required>
                    <label class="form-check-label" for="q117_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q117" id="q117_3" value="3" required>
                    <label class="form-check-label" for="q117_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q117" id="q117_4" value="2" required>
                    <label class="form-check-label" for="q117_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q117" id="q117_5" value="1" required>
                    <label class="form-check-label" for="q117_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 92</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15a/4m15a_(2).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q92" id="q92_1" value="5" required>
                    <label class="form-check-label" for="q92_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q92" id="q92_2" value="4" required>
                    <label class="form-check-label" for="q92_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q92" id="q92_3" value="3" required>
                    <label class="form-check-label" for="q92_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q92" id="q92_4" value="2" required>
                    <label class="form-check-label" for="q92_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q92" id="q92_5" value="1" required>
                    <label class="form-check-label" for="q92_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 14</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15/1m15_(14).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q14" id="q14_1" value="5" required>
                    <label class="form-check-label" for="q14_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q14" id="q14_2" value="4" required>
                    <label class="form-check-label" for="q14_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q14" id="q14_3" value="3" required>
                    <label class="form-check-label" for="q14_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q14" id="q14_4" value="2" required>
                    <label class="form-check-label" for="q14_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q14" id="q14_5" value="1" required>
                    <label class="form-check-label" for="q14_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 7</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15/1m15_(7).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q7" id="q7_1" value="5" required>
                    <label class="form-check-label" for="q7_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q7" id="q7_2" value="4" required>
                    <label class="form-check-label" for="q7_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q7" id="q7_3" value="3" required>
                    <label class="form-check-label" for="q7_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q7" id="q7_4" value="2" required>
                    <label class="form-check-label" for="q7_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q7" id="q7_5" value="1" required>
                    <label class="form-check-label" for="q7_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 87</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15a/2m15a_(12).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q87" id="q87_1" value="5" required>
                    <label class="form-check-label" for="q87_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q87" id="q87_2" value="4" required>
                    <label class="form-check-label" for="q87_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q87" id="q87_3" value="3" required>
                    <label class="form-check-label" for="q87_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q87" id="q87_4" value="2" required>
                    <label class="form-check-label" for="q87_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q87" id="q87_5" value="1" required>
                    <label class="form-check-label" for="q87_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 25</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15/2m15_(10).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q25" id="q25_1" value="5" required>
                    <label class="form-check-label" for="q25_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q25" id="q25_2" value="4" required>
                    <label class="form-check-label" for="q25_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q25" id="q25_3" value="3" required>
                    <label class="form-check-label" for="q25_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q25" id="q25_4" value="2" required>
                    <label class="form-check-label" for="q25_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q25" id="q25_5" value="1" required>
                    <label class="form-check-label" for="q25_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 59</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/16m15/16m15_(14).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q59" id="q59_1" value="5" required>
                    <label class="form-check-label" for="q59_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q59" id="q59_2" value="4" required>
                    <label class="form-check-label" for="q59_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q59" id="q59_3" value="3" required>
                    <label class="form-check-label" for="q59_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q59" id="q59_4" value="2" required>
                    <label class="form-check-label" for="q59_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q59" id="q59_5" value="1" required>
                    <label class="form-check-label" for="q59_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 13</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15/1m15_(13).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q13" id="q13_1" value="5" required>
                    <label class="form-check-label" for="q13_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q13" id="q13_2" value="4" required>
                    <label class="form-check-label" for="q13_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q13" id="q13_3" value="3" required>
                    <label class="form-check-label" for="q13_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q13" id="q13_4" value="2" required>
                    <label class="form-check-label" for="q13_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q13" id="q13_5" value="1" required>
                    <label class="form-check-label" for="q13_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 27</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15/2m15_(12).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q27" id="q27_1" value="5" required>
                    <label class="form-check-label" for="q27_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q27" id="q27_2" value="4" required>
                    <label class="form-check-label" for="q27_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q27" id="q27_3" value="3" required>
                    <label class="form-check-label" for="q27_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q27" id="q27_4" value="2" required>
                    <label class="form-check-label" for="q27_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q27" id="q27_5" value="1" required>
                    <label class="form-check-label" for="q27_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 71</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15a/1m15a_(11).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q71" id="q71_1" value="5" required>
                    <label class="form-check-label" for="q71_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q71" id="q71_2" value="4" required>
                    <label class="form-check-label" for="q71_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q71" id="q71_3" value="3" required>
                    <label class="form-check-label" for="q71_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q71" id="q71_4" value="2" required>
                    <label class="form-check-label" for="q71_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q71" id="q71_5" value="1" required>
                    <label class="form-check-label" for="q71_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 66</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15a/1m15a_(6).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q66" id="q66_1" value="5" required>
                    <label class="form-check-label" for="q66_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q66" id="q66_2" value="4" required>
                    <label class="form-check-label" for="q66_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q66" id="q66_3" value="3" required>
                    <label class="form-check-label" for="q66_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q66" id="q66_4" value="2" required>
                    <label class="form-check-label" for="q66_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q66" id="q66_5" value="1" required>
                    <label class="form-check-label" for="q66_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 16</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15/2m15_(1).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q16" id="q16_1" value="5" required>
                    <label class="form-check-label" for="q16_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q16" id="q16_2" value="4" required>
                    <label class="form-check-label" for="q16_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q16" id="q16_3" value="3" required>
                    <label class="form-check-label" for="q16_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q16" id="q16_4" value="2" required>
                    <label class="form-check-label" for="q16_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q16" id="q16_5" value="1" required>
                    <label class="form-check-label" for="q16_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 81</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15a/2m15a_(6).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q81" id="q81_1" value="5" required>
                    <label class="form-check-label" for="q81_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q81" id="q81_2" value="4" required>
                    <label class="form-check-label" for="q81_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q81" id="q81_3" value="3" required>
                    <label class="form-check-label" for="q81_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q81" id="q81_4" value="2" required>
                    <label class="form-check-label" for="q81_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q81" id="q81_5" value="1" required>
                    <label class="form-check-label" for="q81_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 36</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15/4m15_(6).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q36" id="q36_1" value="5" required>
                    <label class="form-check-label" for="q36_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q36" id="q36_2" value="4" required>
                    <label class="form-check-label" for="q36_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q36" id="q36_3" value="3" required>
                    <label class="form-check-label" for="q36_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q36" id="q36_4" value="2" required>
                    <label class="form-check-label" for="q36_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q36" id="q36_5" value="1" required>
                    <label class="form-check-label" for="q36_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 63</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15a/1m15a_(3).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q63" id="q63_1" value="5" required>
                    <label class="form-check-label" for="q63_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q63" id="q63_2" value="4" required>
                    <label class="form-check-label" for="q63_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q63" id="q63_3" value="3" required>
                    <label class="form-check-label" for="q63_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q63" id="q63_4" value="2" required>
                    <label class="form-check-label" for="q63_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q63" id="q63_5" value="1" required>
                    <label class="form-check-label" for="q63_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 70</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15a/1m15a_(10).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q70" id="q70_1" value="5" required>
                    <label class="form-check-label" for="q70_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q70" id="q70_2" value="4" required>
                    <label class="form-check-label" for="q70_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q70" id="q70_3" value="3" required>
                    <label class="form-check-label" for="q70_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q70" id="q70_4" value="2" required>
                    <label class="form-check-label" for="q70_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q70" id="q70_5" value="1" required>
                    <label class="form-check-label" for="q70_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 32</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15/4m15_(2).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q32" id="q32_1" value="5" required>
                    <label class="form-check-label" for="q32_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q32" id="q32_2" value="4" required>
                    <label class="form-check-label" for="q32_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q32" id="q32_3" value="3" required>
                    <label class="form-check-label" for="q32_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q32" id="q32_4" value="2" required>
                    <label class="form-check-label" for="q32_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q32" id="q32_5" value="1" required>
                    <label class="form-check-label" for="q32_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 61</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15a/1m15a_(1).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q61" id="q61_1" value="5" required>
                    <label class="form-check-label" for="q61_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q61" id="q61_2" value="4" required>
                    <label class="form-check-label" for="q61_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q61" id="q61_3" value="3" required>
                    <label class="form-check-label" for="q61_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q61" id="q61_4" value="2" required>
                    <label class="form-check-label" for="q61_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q61" id="q61_5" value="1" required>
                    <label class="form-check-label" for="q61_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 9</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15/1m15_(9).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q9" id="q9_1" value="5" required>
                    <label class="form-check-label" for="q9_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q9" id="q9_2" value="4" required>
                    <label class="form-check-label" for="q9_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q9" id="q9_3" value="3" required>
                    <label class="form-check-label" for="q9_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q9" id="q9_4" value="2" required>
                    <label class="form-check-label" for="q9_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q9" id="q9_5" value="1" required>
                    <label class="form-check-label" for="q9_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 74</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15a/1m15a_(14).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q74" id="q74_1" value="5" required>
                    <label class="form-check-label" for="q74_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q74" id="q74_2" value="4" required>
                    <label class="form-check-label" for="q74_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q74" id="q74_3" value="3" required>
                    <label class="form-check-label" for="q74_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q74" id="q74_4" value="2" required>
                    <label class="form-check-label" for="q74_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q74" id="q74_5" value="1" required>
                    <label class="form-check-label" for="q74_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 68</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15a/1m15a_(8).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q68" id="q68_1" value="5" required>
                    <label class="form-check-label" for="q68_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q68" id="q68_2" value="4" required>
                    <label class="form-check-label" for="q68_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q68" id="q68_3" value="3" required>
                    <label class="form-check-label" for="q68_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q68" id="q68_4" value="2" required>
                    <label class="form-check-label" for="q68_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q68" id="q68_5" value="1" required>
                    <label class="form-check-label" for="q68_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 31</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15/4m15_(1).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q31" id="q31_1" value="5" required>
                    <label class="form-check-label" for="q31_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q31" id="q31_2" value="4" required>
                    <label class="form-check-label" for="q31_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q31" id="q31_3" value="3" required>
                    <label class="form-check-label" for="q31_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q31" id="q31_4" value="2" required>
                    <label class="form-check-label" for="q31_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q31" id="q31_5" value="1" required>
                    <label class="form-check-label" for="q31_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 12</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15/1m15_(12).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q12" id="q12_1" value="5" required>
                    <label class="form-check-label" for="q12_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q12" id="q12_2" value="4" required>
                    <label class="form-check-label" for="q12_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q12" id="q12_3" value="3" required>
                    <label class="form-check-label" for="q12_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q12" id="q12_4" value="2" required>
                    <label class="form-check-label" for="q12_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q12" id="q12_5" value="1" required>
                    <label class="form-check-label" for="q12_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 106</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/gt15/lien-96-0006.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q106" id="q106_1" value="5" required>
                    <label class="form-check-label" for="q106_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q106" id="q106_2" value="4" required>
                    <label class="form-check-label" for="q106_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q106" id="q106_3" value="3" required>
                    <label class="form-check-label" for="q106_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q106" id="q106_4" value="2" required>
                    <label class="form-check-label" for="q106_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q106" id="q106_5" value="1" required>
                    <label class="form-check-label" for="q106_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 33</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15/4m15_(3).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q33" id="q33_1" value="5" required>
                    <label class="form-check-label" for="q33_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q33" id="q33_2" value="4" required>
                    <label class="form-check-label" for="q33_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q33" id="q33_3" value="3" required>
                    <label class="form-check-label" for="q33_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q33" id="q33_4" value="2" required>
                    <label class="form-check-label" for="q33_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q33" id="q33_5" value="1" required>
                    <label class="form-check-label" for="q33_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 113</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/gt15/lien-103-0006.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q113" id="q113_1" value="5" required>
                    <label class="form-check-label" for="q113_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q113" id="q113_2" value="4" required>
                    <label class="form-check-label" for="q113_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q113" id="q113_3" value="3" required>
                    <label class="form-check-label" for="q113_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q113" id="q113_4" value="2" required>
                    <label class="form-check-label" for="q113_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q113" id="q113_5" value="1" required>
                    <label class="form-check-label" for="q113_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 50</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/16m15/16m15_(5).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q50" id="q50_1" value="5" required>
                    <label class="form-check-label" for="q50_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q50" id="q50_2" value="4" required>
                    <label class="form-check-label" for="q50_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q50" id="q50_3" value="3" required>
                    <label class="form-check-label" for="q50_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q50" id="q50_4" value="2" required>
                    <label class="form-check-label" for="q50_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q50" id="q50_5" value="1" required>
                    <label class="form-check-label" for="q50_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 62</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15a/1m15a_(2).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q62" id="q62_1" value="5" required>
                    <label class="form-check-label" for="q62_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q62" id="q62_2" value="4" required>
                    <label class="form-check-label" for="q62_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q62" id="q62_3" value="3" required>
                    <label class="form-check-label" for="q62_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q62" id="q62_4" value="2" required>
                    <label class="form-check-label" for="q62_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q62" id="q62_5" value="1" required>
                    <label class="form-check-label" for="q62_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 77</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15a/2m15a_(2).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q77" id="q77_1" value="5" required>
                    <label class="form-check-label" for="q77_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q77" id="q77_2" value="4" required>
                    <label class="form-check-label" for="q77_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q77" id="q77_3" value="3" required>
                    <label class="form-check-label" for="q77_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q77" id="q77_4" value="2" required>
                    <label class="form-check-label" for="q77_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q77" id="q77_5" value="1" required>
                    <label class="form-check-label" for="q77_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 80</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15a/2m15a_(5).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q80" id="q80_1" value="5" required>
                    <label class="form-check-label" for="q80_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q80" id="q80_2" value="4" required>
                    <label class="form-check-label" for="q80_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q80" id="q80_3" value="3" required>
                    <label class="form-check-label" for="q80_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q80" id="q80_4" value="2" required>
                    <label class="form-check-label" for="q80_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q80" id="q80_5" value="1" required>
                    <label class="form-check-label" for="q80_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 38</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15/4m15_(8).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q38" id="q38_1" value="5" required>
                    <label class="form-check-label" for="q38_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q38" id="q38_2" value="4" required>
                    <label class="form-check-label" for="q38_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q38" id="q38_3" value="3" required>
                    <label class="form-check-label" for="q38_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q38" id="q38_4" value="2" required>
                    <label class="form-check-label" for="q38_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q38" id="q38_5" value="1" required>
                    <label class="form-check-label" for="q38_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 3</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15/1m15_(3).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q3" id="q3_1" value="5" required>
                    <label class="form-check-label" for="q3_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q3" id="q3_2" value="4" required>
                    <label class="form-check-label" for="q3_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q3" id="q3_3" value="3" required>
                    <label class="form-check-label" for="q3_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q3" id="q3_4" value="2" required>
                    <label class="form-check-label" for="q3_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q3" id="q3_5" value="1" required>
                    <label class="form-check-label" for="q3_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 96</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15a/4m15a_(6).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q96" id="q96_1" value="5" required>
                    <label class="form-check-label" for="q96_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q96" id="q96_2" value="4" required>
                    <label class="form-check-label" for="q96_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q96" id="q96_3" value="3" required>
                    <label class="form-check-label" for="q96_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q96" id="q96_4" value="2" required>
                    <label class="form-check-label" for="q96_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q96" id="q96_5" value="1" required>
                    <label class="form-check-label" for="q96_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 52</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/16m15/16m15_(7).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q52" id="q52_1" value="5" required>
                    <label class="form-check-label" for="q52_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q52" id="q52_2" value="4" required>
                    <label class="form-check-label" for="q52_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q52" id="q52_3" value="3" required>
                    <label class="form-check-label" for="q52_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q52" id="q52_4" value="2" required>
                    <label class="form-check-label" for="q52_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q52" id="q52_5" value="1" required>
                    <label class="form-check-label" for="q52_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 5</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15/1m15_(5).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q5" id="q5_1" value="5" required>
                    <label class="form-check-label" for="q5_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q5" id="q5_2" value="4" required>
                    <label class="form-check-label" for="q5_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q5" id="q5_3" value="3" required>
                    <label class="form-check-label" for="q5_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q5" id="q5_4" value="2" required>
                    <label class="form-check-label" for="q5_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q5" id="q5_5" value="1" required>
                    <label class="form-check-label" for="q5_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 4</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15/1m15_(4).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q4" id="q4_1" value="5" required>
                    <label class="form-check-label" for="q4_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q4" id="q4_2" value="4" required>
                    <label class="form-check-label" for="q4_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q4" id="q4_3" value="3" required>
                    <label class="form-check-label" for="q4_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q4" id="q4_4" value="2" required>
                    <label class="form-check-label" for="q4_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q4" id="q4_5" value="1" required>
                    <label class="form-check-label" for="q4_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 114</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/gt15/lien-103-0007.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q114" id="q114_1" value="5" required>
                    <label class="form-check-label" for="q114_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q114" id="q114_2" value="4" required>
                    <label class="form-check-label" for="q114_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q114" id="q114_3" value="3" required>
                    <label class="form-check-label" for="q114_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q114" id="q114_4" value="2" required>
                    <label class="form-check-label" for="q114_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q114" id="q114_5" value="1" required>
                    <label class="form-check-label" for="q114_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 78</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15a/2m15a_(3).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q78" id="q78_1" value="5" required>
                    <label class="form-check-label" for="q78_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q78" id="q78_2" value="4" required>
                    <label class="form-check-label" for="q78_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q78" id="q78_3" value="3" required>
                    <label class="form-check-label" for="q78_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q78" id="q78_4" value="2" required>
                    <label class="form-check-label" for="q78_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q78" id="q78_5" value="1" required>
                    <label class="form-check-label" for="q78_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 75</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15a/1m15a_(15).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q75" id="q75_1" value="5" required>
                    <label class="form-check-label" for="q75_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q75" id="q75_2" value="4" required>
                    <label class="form-check-label" for="q75_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q75" id="q75_3" value="3" required>
                    <label class="form-check-label" for="q75_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q75" id="q75_4" value="2" required>
                    <label class="form-check-label" for="q75_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q75" id="q75_5" value="1" required>
                    <label class="form-check-label" for="q75_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 11</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15/1m15_(11).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q11" id="q11_1" value="5" required>
                    <label class="form-check-label" for="q11_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q11" id="q11_2" value="4" required>
                    <label class="form-check-label" for="q11_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q11" id="q11_3" value="3" required>
                    <label class="form-check-label" for="q11_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q11" id="q11_4" value="2" required>
                    <label class="form-check-label" for="q11_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q11" id="q11_5" value="1" required>
                    <label class="form-check-label" for="q11_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 23</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15/2m15_(8).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q23" id="q23_1" value="5" required>
                    <label class="form-check-label" for="q23_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q23" id="q23_2" value="4" required>
                    <label class="form-check-label" for="q23_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q23" id="q23_3" value="3" required>
                    <label class="form-check-label" for="q23_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q23" id="q23_4" value="2" required>
                    <label class="form-check-label" for="q23_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q23" id="q23_5" value="1" required>
                    <label class="form-check-label" for="q23_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 82</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15a/2m15a_(7).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q82" id="q82_1" value="5" required>
                    <label class="form-check-label" for="q82_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q82" id="q82_2" value="4" required>
                    <label class="form-check-label" for="q82_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q82" id="q82_3" value="3" required>
                    <label class="form-check-label" for="q82_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q82" id="q82_4" value="2" required>
                    <label class="form-check-label" for="q82_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q82" id="q82_5" value="1" required>
                    <label class="form-check-label" for="q82_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 69</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15a/1m15a_(9).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q69" id="q69_1" value="5" required>
                    <label class="form-check-label" for="q69_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q69" id="q69_2" value="4" required>
                    <label class="form-check-label" for="q69_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q69" id="q69_3" value="3" required>
                    <label class="form-check-label" for="q69_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q69" id="q69_4" value="2" required>
                    <label class="form-check-label" for="q69_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q69" id="q69_5" value="1" required>
                    <label class="form-check-label" for="q69_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 98</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15a/4m15a_(8).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q98" id="q98_1" value="5" required>
                    <label class="form-check-label" for="q98_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q98" id="q98_2" value="4" required>
                    <label class="form-check-label" for="q98_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q98" id="q98_3" value="3" required>
                    <label class="form-check-label" for="q98_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q98" id="q98_4" value="2" required>
                    <label class="form-check-label" for="q98_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q98" id="q98_5" value="1" required>
                    <label class="form-check-label" for="q98_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 49</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/16m15/16m15_(4).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q49" id="q49_1" value="5" required>
                    <label class="form-check-label" for="q49_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q49" id="q49_2" value="4" required>
                    <label class="form-check-label" for="q49_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q49" id="q49_3" value="3" required>
                    <label class="form-check-label" for="q49_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q49" id="q49_4" value="2" required>
                    <label class="form-check-label" for="q49_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q49" id="q49_5" value="1" required>
                    <label class="form-check-label" for="q49_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 48</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/16m15/16m15_(3).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q48" id="q48_1" value="5" required>
                    <label class="form-check-label" for="q48_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q48" id="q48_2" value="4" required>
                    <label class="form-check-label" for="q48_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q48" id="q48_3" value="3" required>
                    <label class="form-check-label" for="q48_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q48" id="q48_4" value="2" required>
                    <label class="form-check-label" for="q48_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q48" id="q48_5" value="1" required>
                    <label class="form-check-label" for="q48_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 26</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15/2m15_(11).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q26" id="q26_1" value="5" required>
                    <label class="form-check-label" for="q26_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q26" id="q26_2" value="4" required>
                    <label class="form-check-label" for="q26_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q26" id="q26_3" value="3" required>
                    <label class="form-check-label" for="q26_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q26" id="q26_4" value="2" required>
                    <label class="form-check-label" for="q26_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q26" id="q26_5" value="1" required>
                    <label class="form-check-label" for="q26_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 18</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15/2m15_(3).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q18" id="q18_1" value="5" required>
                    <label class="form-check-label" for="q18_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q18" id="q18_2" value="4" required>
                    <label class="form-check-label" for="q18_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q18" id="q18_3" value="3" required>
                    <label class="form-check-label" for="q18_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q18" id="q18_4" value="2" required>
                    <label class="form-check-label" for="q18_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q18" id="q18_5" value="1" required>
                    <label class="form-check-label" for="q18_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 42</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15/4m15_(12).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q42" id="q42_1" value="5" required>
                    <label class="form-check-label" for="q42_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q42" id="q42_2" value="4" required>
                    <label class="form-check-label" for="q42_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q42" id="q42_3" value="3" required>
                    <label class="form-check-label" for="q42_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q42" id="q42_4" value="2" required>
                    <label class="form-check-label" for="q42_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q42" id="q42_5" value="1" required>
                    <label class="form-check-label" for="q42_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 107</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/gt15/lien-97-0001.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q107" id="q107_1" value="5" required>
                    <label class="form-check-label" for="q107_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q107" id="q107_2" value="4" required>
                    <label class="form-check-label" for="q107_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q107" id="q107_3" value="3" required>
                    <label class="form-check-label" for="q107_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q107" id="q107_4" value="2" required>
                    <label class="form-check-label" for="q107_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q107" id="q107_5" value="1" required>
                    <label class="form-check-label" for="q107_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 116</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/gt15/lien-104-0018.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q116" id="q116_1" value="5" required>
                    <label class="form-check-label" for="q116_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q116" id="q116_2" value="4" required>
                    <label class="form-check-label" for="q116_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q116" id="q116_3" value="3" required>
                    <label class="form-check-label" for="q116_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q116" id="q116_4" value="2" required>
                    <label class="form-check-label" for="q116_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q116" id="q116_5" value="1" required>
                    <label class="form-check-label" for="q116_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 21</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15/2m15_(6).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q21" id="q21_1" value="5" required>
                    <label class="form-check-label" for="q21_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q21" id="q21_2" value="4" required>
                    <label class="form-check-label" for="q21_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q21" id="q21_3" value="3" required>
                    <label class="form-check-label" for="q21_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q21" id="q21_4" value="2" required>
                    <label class="form-check-label" for="q21_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q21" id="q21_5" value="1" required>
                    <label class="form-check-label" for="q21_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 110</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/gt15/lien-98-0003.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q110" id="q110_1" value="5" required>
                    <label class="form-check-label" for="q110_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q110" id="q110_2" value="4" required>
                    <label class="form-check-label" for="q110_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q110" id="q110_3" value="3" required>
                    <label class="form-check-label" for="q110_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q110" id="q110_4" value="2" required>
                    <label class="form-check-label" for="q110_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q110" id="q110_5" value="1" required>
                    <label class="form-check-label" for="q110_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 120</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/gt15/lien-106-0002.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q120" id="q120_1" value="5" required>
                    <label class="form-check-label" for="q120_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q120" id="q120_2" value="4" required>
                    <label class="form-check-label" for="q120_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q120" id="q120_3" value="3" required>
                    <label class="form-check-label" for="q120_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q120" id="q120_4" value="2" required>
                    <label class="form-check-label" for="q120_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q120" id="q120_5" value="1" required>
                    <label class="form-check-label" for="q120_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 64</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15a/1m15a_(4).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q64" id="q64_1" value="5" required>
                    <label class="form-check-label" for="q64_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q64" id="q64_2" value="4" required>
                    <label class="form-check-label" for="q64_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q64" id="q64_3" value="3" required>
                    <label class="form-check-label" for="q64_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q64" id="q64_4" value="2" required>
                    <label class="form-check-label" for="q64_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q64" id="q64_5" value="1" required>
                    <label class="form-check-label" for="q64_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 73</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15a/1m15a_(13).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q73" id="q73_1" value="5" required>
                    <label class="form-check-label" for="q73_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q73" id="q73_2" value="4" required>
                    <label class="form-check-label" for="q73_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q73" id="q73_3" value="3" required>
                    <label class="form-check-label" for="q73_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q73" id="q73_4" value="2" required>
                    <label class="form-check-label" for="q73_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q73" id="q73_5" value="1" required>
                    <label class="form-check-label" for="q73_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 101</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15a/4m15a_(11).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q101" id="q101_1" value="5" required>
                    <label class="form-check-label" for="q101_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q101" id="q101_2" value="4" required>
                    <label class="form-check-label" for="q101_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q101" id="q101_3" value="3" required>
                    <label class="form-check-label" for="q101_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q101" id="q101_4" value="2" required>
                    <label class="form-check-label" for="q101_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q101" id="q101_5" value="1" required>
                    <label class="form-check-label" for="q101_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 95</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15a/4m15a_(5).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q95" id="q95_1" value="5" required>
                    <label class="form-check-label" for="q95_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q95" id="q95_2" value="4" required>
                    <label class="form-check-label" for="q95_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q95" id="q95_3" value="3" required>
                    <label class="form-check-label" for="q95_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q95" id="q95_4" value="2" required>
                    <label class="form-check-label" for="q95_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q95" id="q95_5" value="1" required>
                    <label class="form-check-label" for="q95_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 15</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15/1m15_(15).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q15" id="q15_1" value="5" required>
                    <label class="form-check-label" for="q15_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q15" id="q15_2" value="4" required>
                    <label class="form-check-label" for="q15_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q15" id="q15_3" value="3" required>
                    <label class="form-check-label" for="q15_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q15" id="q15_4" value="2" required>
                    <label class="form-check-label" for="q15_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q15" id="q15_5" value="1" required>
                    <label class="form-check-label" for="q15_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 94</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15a/4m15a_(4).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q94" id="q94_1" value="5" required>
                    <label class="form-check-label" for="q94_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q94" id="q94_2" value="4" required>
                    <label class="form-check-label" for="q94_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q94" id="q94_3" value="3" required>
                    <label class="form-check-label" for="q94_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q94" id="q94_4" value="2" required>
                    <label class="form-check-label" for="q94_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q94" id="q94_5" value="1" required>
                    <label class="form-check-label" for="q94_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 19</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15/2m15_(4).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q19" id="q19_1" value="5" required>
                    <label class="form-check-label" for="q19_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q19" id="q19_2" value="4" required>
                    <label class="form-check-label" for="q19_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q19" id="q19_3" value="3" required>
                    <label class="form-check-label" for="q19_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q19" id="q19_4" value="2" required>
                    <label class="form-check-label" for="q19_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q19" id="q19_5" value="1" required>
                    <label class="form-check-label" for="q19_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 65</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15a/1m15a_(5).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q65" id="q65_1" value="5" required>
                    <label class="form-check-label" for="q65_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q65" id="q65_2" value="4" required>
                    <label class="form-check-label" for="q65_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q65" id="q65_3" value="3" required>
                    <label class="form-check-label" for="q65_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q65" id="q65_4" value="2" required>
                    <label class="form-check-label" for="q65_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q65" id="q65_5" value="1" required>
                    <label class="form-check-label" for="q65_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 35</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15/4m15_(5).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q35" id="q35_1" value="5" required>
                    <label class="form-check-label" for="q35_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q35" id="q35_2" value="4" required>
                    <label class="form-check-label" for="q35_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q35" id="q35_3" value="3" required>
                    <label class="form-check-label" for="q35_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q35" id="q35_4" value="2" required>
                    <label class="form-check-label" for="q35_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q35" id="q35_5" value="1" required>
                    <label class="form-check-label" for="q35_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 103</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15a/4m15a_(13).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q103" id="q103_1" value="5" required>
                    <label class="form-check-label" for="q103_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q103" id="q103_2" value="4" required>
                    <label class="form-check-label" for="q103_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q103" id="q103_3" value="3" required>
                    <label class="form-check-label" for="q103_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q103" id="q103_4" value="2" required>
                    <label class="form-check-label" for="q103_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q103" id="q103_5" value="1" required>
                    <label class="form-check-label" for="q103_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 20</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15/2m15_(5).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q20" id="q20_1" value="5" required>
                    <label class="form-check-label" for="q20_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q20" id="q20_2" value="4" required>
                    <label class="form-check-label" for="q20_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q20" id="q20_3" value="3" required>
                    <label class="form-check-label" for="q20_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q20" id="q20_4" value="2" required>
                    <label class="form-check-label" for="q20_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q20" id="q20_5" value="1" required>
                    <label class="form-check-label" for="q20_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 112</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/gt15/lien-98-0005.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q112" id="q112_1" value="5" required>
                    <label class="form-check-label" for="q112_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q112" id="q112_2" value="4" required>
                    <label class="form-check-label" for="q112_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q112" id="q112_3" value="3" required>
                    <label class="form-check-label" for="q112_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q112" id="q112_4" value="2" required>
                    <label class="form-check-label" for="q112_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q112" id="q112_5" value="1" required>
                    <label class="form-check-label" for="q112_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 53</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/16m15/16m15_(8).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q53" id="q53_1" value="5" required>
                    <label class="form-check-label" for="q53_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q53" id="q53_2" value="4" required>
                    <label class="form-check-label" for="q53_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q53" id="q53_3" value="3" required>
                    <label class="form-check-label" for="q53_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q53" id="q53_4" value="2" required>
                    <label class="form-check-label" for="q53_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q53" id="q53_5" value="1" required>
                    <label class="form-check-label" for="q53_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 34</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15/4m15_(4).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q34" id="q34_1" value="5" required>
                    <label class="form-check-label" for="q34_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q34" id="q34_2" value="4" required>
                    <label class="form-check-label" for="q34_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q34" id="q34_3" value="3" required>
                    <label class="form-check-label" for="q34_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q34" id="q34_4" value="2" required>
                    <label class="form-check-label" for="q34_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q34" id="q34_5" value="1" required>
                    <label class="form-check-label" for="q34_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 17</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15/2m15_(2).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q17" id="q17_1" value="5" required>
                    <label class="form-check-label" for="q17_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q17" id="q17_2" value="4" required>
                    <label class="form-check-label" for="q17_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q17" id="q17_3" value="3" required>
                    <label class="form-check-label" for="q17_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q17" id="q17_4" value="2" required>
                    <label class="form-check-label" for="q17_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q17" id="q17_5" value="1" required>
                    <label class="form-check-label" for="q17_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 97</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15a/4m15a_(7).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q97" id="q97_1" value="5" required>
                    <label class="form-check-label" for="q97_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q97" id="q97_2" value="4" required>
                    <label class="form-check-label" for="q97_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q97" id="q97_3" value="3" required>
                    <label class="form-check-label" for="q97_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q97" id="q97_4" value="2" required>
                    <label class="form-check-label" for="q97_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q97" id="q97_5" value="1" required>
                    <label class="form-check-label" for="q97_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 28</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15/2m15_(13).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q28" id="q28_1" value="5" required>
                    <label class="form-check-label" for="q28_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q28" id="q28_2" value="4" required>
                    <label class="form-check-label" for="q28_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q28" id="q28_3" value="3" required>
                    <label class="form-check-label" for="q28_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q28" id="q28_4" value="2" required>
                    <label class="form-check-label" for="q28_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q28" id="q28_5" value="1" required>
                    <label class="form-check-label" for="q28_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 51</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/16m15/16m15_(6).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q51" id="q51_1" value="5" required>
                    <label class="form-check-label" for="q51_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q51" id="q51_2" value="4" required>
                    <label class="form-check-label" for="q51_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q51" id="q51_3" value="3" required>
                    <label class="form-check-label" for="q51_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q51" id="q51_4" value="2" required>
                    <label class="form-check-label" for="q51_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q51" id="q51_5" value="1" required>
                    <label class="form-check-label" for="q51_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 115</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/gt15/lien-104-0004.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q115" id="q115_1" value="5" required>
                    <label class="form-check-label" for="q115_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q115" id="q115_2" value="4" required>
                    <label class="form-check-label" for="q115_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q115" id="q115_3" value="3" required>
                    <label class="form-check-label" for="q115_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q115" id="q115_4" value="2" required>
                    <label class="form-check-label" for="q115_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q115" id="q115_5" value="1" required>
                    <label class="form-check-label" for="q115_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 89</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15a/2m15a_(14).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q89" id="q89_1" value="5" required>
                    <label class="form-check-label" for="q89_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q89" id="q89_2" value="4" required>
                    <label class="form-check-label" for="q89_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q89" id="q89_3" value="3" required>
                    <label class="form-check-label" for="q89_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q89" id="q89_4" value="2" required>
                    <label class="form-check-label" for="q89_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q89" id="q89_5" value="1" required>
                    <label class="form-check-label" for="q89_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 43</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15/4m15_(13).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q43" id="q43_1" value="5" required>
                    <label class="form-check-label" for="q43_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q43" id="q43_2" value="4" required>
                    <label class="form-check-label" for="q43_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q43" id="q43_3" value="3" required>
                    <label class="form-check-label" for="q43_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q43" id="q43_4" value="2" required>
                    <label class="form-check-label" for="q43_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q43" id="q43_5" value="1" required>
                    <label class="form-check-label" for="q43_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 109</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/gt15/lien-98-0002.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q109" id="q109_1" value="5" required>
                    <label class="form-check-label" for="q109_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q109" id="q109_2" value="4" required>
                    <label class="form-check-label" for="q109_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q109" id="q109_3" value="3" required>
                    <label class="form-check-label" for="q109_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q109" id="q109_4" value="2" required>
                    <label class="form-check-label" for="q109_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q109" id="q109_5" value="1" required>
                    <label class="form-check-label" for="q109_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 99</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15a/4m15a_(9).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q99" id="q99_1" value="5" required>
                    <label class="form-check-label" for="q99_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q99" id="q99_2" value="4" required>
                    <label class="form-check-label" for="q99_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q99" id="q99_3" value="3" required>
                    <label class="form-check-label" for="q99_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q99" id="q99_4" value="2" required>
                    <label class="form-check-label" for="q99_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q99" id="q99_5" value="1" required>
                    <label class="form-check-label" for="q99_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 47</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/16m15/16m15_(2).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q47" id="q47_1" value="5" required>
                    <label class="form-check-label" for="q47_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q47" id="q47_2" value="4" required>
                    <label class="form-check-label" for="q47_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q47" id="q47_3" value="3" required>
                    <label class="form-check-label" for="q47_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q47" id="q47_4" value="2" required>
                    <label class="form-check-label" for="q47_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q47" id="q47_5" value="1" required>
                    <label class="form-check-label" for="q47_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 93</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15a/4m15a_(3).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q93" id="q93_1" value="5" required>
                    <label class="form-check-label" for="q93_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q93" id="q93_2" value="4" required>
                    <label class="form-check-label" for="q93_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q93" id="q93_3" value="3" required>
                    <label class="form-check-label" for="q93_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q93" id="q93_4" value="2" required>
                    <label class="form-check-label" for="q93_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q93" id="q93_5" value="1" required>
                    <label class="form-check-label" for="q93_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 6</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15/1m15_(6).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q6" id="q6_1" value="5" required>
                    <label class="form-check-label" for="q6_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q6" id="q6_2" value="4" required>
                    <label class="form-check-label" for="q6_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q6" id="q6_3" value="3" required>
                    <label class="form-check-label" for="q6_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q6" id="q6_4" value="2" required>
                    <label class="form-check-label" for="q6_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q6" id="q6_5" value="1" required>
                    <label class="form-check-label" for="q6_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 58</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/16m15/16m15_(13).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q58" id="q58_1" value="5" required>
                    <label class="form-check-label" for="q58_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q58" id="q58_2" value="4" required>
                    <label class="form-check-label" for="q58_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q58" id="q58_3" value="3" required>
                    <label class="form-check-label" for="q58_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q58" id="q58_4" value="2" required>
                    <label class="form-check-label" for="q58_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q58" id="q58_5" value="1" required>
                    <label class="form-check-label" for="q58_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 90</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15a/2m15a_(15).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q90" id="q90_1" value="5" required>
                    <label class="form-check-label" for="q90_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q90" id="q90_2" value="4" required>
                    <label class="form-check-label" for="q90_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q90" id="q90_3" value="3" required>
                    <label class="form-check-label" for="q90_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q90" id="q90_4" value="2" required>
                    <label class="form-check-label" for="q90_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q90" id="q90_5" value="1" required>
                    <label class="form-check-label" for="q90_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 57</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/16m15/16m15_(12).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q57" id="q57_1" value="5" required>
                    <label class="form-check-label" for="q57_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q57" id="q57_2" value="4" required>
                    <label class="form-check-label" for="q57_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q57" id="q57_3" value="3" required>
                    <label class="form-check-label" for="q57_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q57" id="q57_4" value="2" required>
                    <label class="form-check-label" for="q57_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q57" id="q57_5" value="1" required>
                    <label class="form-check-label" for="q57_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 30</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15/2m15_(15).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q30" id="q30_1" value="5" required>
                    <label class="form-check-label" for="q30_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q30" id="q30_2" value="4" required>
                    <label class="form-check-label" for="q30_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q30" id="q30_3" value="3" required>
                    <label class="form-check-label" for="q30_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q30" id="q30_4" value="2" required>
                    <label class="form-check-label" for="q30_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q30" id="q30_5" value="1" required>
                    <label class="form-check-label" for="q30_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 1</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15/1m15_(1).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q1" id="q1_1" value="5" required>
                    <label class="form-check-label" for="q1_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q1" id="q1_2" value="4" required>
                    <label class="form-check-label" for="q1_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q1" id="q1_3" value="3" required>
                    <label class="form-check-label" for="q1_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q1" id="q1_4" value="2" required>
                    <label class="form-check-label" for="q1_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q1" id="q1_5" value="1" required>
                    <label class="form-check-label" for="q1_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 111</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/gt15/lien-98-0004.wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q111" id="q111_1" value="5" required>
                    <label class="form-check-label" for="q111_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q111" id="q111_2" value="4" required>
                    <label class="form-check-label" for="q111_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q111" id="q111_3" value="3" required>
                    <label class="form-check-label" for="q111_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q111" id="q111_4" value="2" required>
                    <label class="form-check-label" for="q111_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q111" id="q111_5" value="1" required>
                    <label class="form-check-label" for="q111_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 84</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15a/2m15a_(9).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q84" id="q84_1" value="5" required>
                    <label class="form-check-label" for="q84_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q84" id="q84_2" value="4" required>
                    <label class="form-check-label" for="q84_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q84" id="q84_3" value="3" required>
                    <label class="form-check-label" for="q84_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q84" id="q84_4" value="2" required>
                    <label class="form-check-label" for="q84_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q84" id="q84_5" value="1" required>
                    <label class="form-check-label" for="q84_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 88</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/2m15a/2m15a_(13).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q88" id="q88_1" value="5" required>
                    <label class="form-check-label" for="q88_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q88" id="q88_2" value="4" required>
                    <label class="form-check-label" for="q88_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q88" id="q88_3" value="3" required>
                    <label class="form-check-label" for="q88_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q88" id="q88_4" value="2" required>
                    <label class="form-check-label" for="q88_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q88" id="q88_5" value="1" required>
                    <label class="form-check-label" for="q88_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 8</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/1m15/1m15_(8).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q8" id="q8_1" value="5" required>
                    <label class="form-check-label" for="q8_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q8" id="q8_2" value="4" required>
                    <label class="form-check-label" for="q8_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q8" id="q8_3" value="3" required>
                    <label class="form-check-label" for="q8_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q8" id="q8_4" value="2" required>
                    <label class="form-check-label" for="q8_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q8" id="q8_5" value="1" required>
                    <label class="form-check-label" for="q8_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 104</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15a/4m15a_(14).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q104" id="q104_1" value="5" required>
                    <label class="form-check-label" for="q104_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q104" id="q104_2" value="4" required>
                    <label class="form-check-label" for="q104_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q104" id="q104_3" value="3" required>
                    <label class="form-check-label" for="q104_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q104" id="q104_4" value="2" required>
                    <label class="form-check-label" for="q104_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q104" id="q104_5" value="1" required>
                    <label class="form-check-label" for="q104_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 45</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15/4m15_(15).mp3">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q45" id="q45_1" value="5" required>
                    <label class="form-check-label" for="q45_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q45" id="q45_2" value="4" required>
                    <label class="form-check-label" for="q45_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q45" id="q45_3" value="3" required>
                    <label class="form-check-label" for="q45_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q45" id="q45_4" value="2" required>
                    <label class="form-check-label" for="q45_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q45" id="q45_5" value="1" required>
                    <label class="form-check-label" for="q45_5">1（Tệ）</label>
                </div>
            </div>
        </div> 
        <div class="card form-group">
            <div class="card-header">Câu 105</div>
            <div class="card-body">
                <p>
                    <audio controls src="wavs/mmos/4m15a/4m15a_(15).wav">
                        Your browser does not support the audio element.
                    </audio>
                </p>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q105" id="q105_1" value="5" required>
                    <label class="form-check-label" for="q105_1">5（Rất tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q105" id="q105_2" value="4" required>
                    <label class="form-check-label" for="q105_2">4（Tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q105" id="q105_3" value="3" required>
                    <label class="form-check-label" for="q105_3">3（Bình thường）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q105" id="q105_4" value="2" required>
                    <label class="form-check-label" for="q105_4">2（Không tốt）</label>
                </div>
                <div class="form-check">
                    <input class="form-check-input" type="radio" name="q105" id="q105_5" value="1" required>
                    <label class="form-check-label" for="q105_5">1（Tệ）</label>
                </div>
            </div>
        </div> 


                




            <input type="text" name="formid" value="1" hidden>
            <input type="text" name="thank" value="Cảm ơn bạn một lần nữa vì đã tham gia thử nghiệm này！" hidden>
            <input class="btn btn-info btn-lg" type="submit" value="Gửi kết quả" id="submitBtn">
            <p class="text-muted">
                <small>Nếu bạn thấy không trả được khi nộp kết quả vui lòng kiểm tra lại xem bạn đã điền tên mình chưa và đã trả lời được mọi câu hỏi chưa, xin cảm ơn!</small>
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
