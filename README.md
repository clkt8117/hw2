# 作業二－電商前端應用
<!DOCTYPE html>
<html lang="zh-TW">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>作業二 - 電商前端應用</title>

 
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <link rel="stylesheet" href="/index.css">
</head>

<body>

    <div class="container">
        <div class="jumbotron">
            <h1>作業二 - 電商前端應用</h1>
        </div>

        <!-- 工具列 -->
        <div class="form-group row">
            <div class="col">
                <button id="query" type="button" class="btn btn-primary">查詢</button>
            </div>
        </div>
        <div class="form-group row">
            <div class="col">
                <button id="query" type="button" class="btn btn-primary">新增</button>
                <li href="file:///Users/tingchen/Desktop/%E4%BD%9C%E6%A5%AD2/%E6%96%B0%E5%A2%9E/index.html"></li>
            </div>
        </div>

        <!-- 產品列表 -->

        <div class="container-fluid bg-3 text-center">
            <div class="row">
                <div class="col-sm-4">
                    <img src="01.jpg" alt="Image" style="width: 90% ">
                    <h5>路由器</h5>
                    <h7>NT$727</h7>
                </div>
                <div class="col-sm-4">
                    <img src="02.jpg" alt="Image" style="width: 90% ">
                    <h5>小米手環</h5>
                    <h7>NT$325</h7>
                </div>
                <div class="col-sm-4">
                    <img src="03.jpg" alt="Image" style="width: 90% ">
                    <h5>小米行動電源</h5>
                    <h7>NT$699</h7>
                </div>
            </div>
        </div>

        <div class="container-fluid bg-3 text-center">
            <div class="row">
                <div class="col-sm-4">
                    <img src="03.jpg" alt="Image" style="width: 90% ">
                    <h5>小米行動電源</h5>
                    <h7>NT$699</h7>
                </div>
                <div class="col-sm-4">
                    <img src="02.jpg" alt="Image" style="width: 90% ">
                    <h5>小米手環</h5>
                    <h7>NT$325</h7>
                </div>
                <div class="col-sm-4">

                    <img src="01.jpg" alt="Image" style="width: 90% ">
                    <h5>路由器</h5>
                    <h7>NT$727</h7>
                </div>
            </div>
        </div>

        <div class="container-fluid bg-3 text-center">
            <div class="row">
                <div class="col-sm-4">
                    <img src="03.jpg" alt="Image" style="width: 90% ">
                    <h5>小米行動電源</h5>
                    <h7>NT$699</h7>
                </div>
                <div class="col-sm-4">
                    <img src="01.jpg" alt="Image" style="width: 90% ">
                    <h5>路由器</h5>
                    <h7>NT$727</h7>
                </div>
                <div class="col-sm-4">
                    <img src="02.jpg" alt="Image" style="width: 90% ">
                    <h5>小米手環</h5>
                    <h7>NT$711</h7>
                </div>
            </div>
        </div>

        <div class="container-fluid bg-3 text-center">
            <div class="row">
                <div class="col-sm-4">
                    <img src="01.jpg" alt="Image" style="width: 90% ">
                    <h5>路由器</h5>
                    <h7>NT$727</h7>
                </div>
                <div class="col-sm-4">
                    <img src="02.jpg" alt="Image" style="width: 90% ">
                    <h5>小米手環</h5>
                    <h7>NT$325</h7>
                </div>
                <div class="col-sm-4">
                    <img src="03.jpg" alt="Image" style="width: 90% ">
                    <h5>小米行動電源</h5>
                    <h7>NT$699</h7>
                </div>
            </div>
        </div>


        <!-- 分頁 -->
        <div class="row" id="page">
            <div class="col">
                <nav aria-label="Page navigation example">
                    <ul id="page-number" class="pagination justify-content-center">
                        <li class="page-item disabled">
                            <a class="page-link" href="#" tabindex="-1" aria-disabled="true">&laquo;</a>
                        </li>
                        <li class="page-item active"><a class="page-link" href="#">1</a></li>
                        <li class="page-item"><a class="page-link" href="file:///Users/tingchen/Desktop/作業2/第二頁/index.html">2</a></li>
                        <li class="page-item"><a class="page-link" href="file:///Users/tingchen/Desktop/%E4%BD%9C%E6%A5%AD2/%E7%AC%AC%E4%B8%89%E9%A0%81/index.html">3</a></li>
                        <li class="page-item">
                            <a class="page-link" href="#">&raquo;</a>
                        </li>
                    </ul>
                </nav>
            </div>
        </div>


        <!-- 頁尾 -->
        <footer>
            <div class="text-center">
                2019 &copy; 前端程式設計
            </div>
        </footer>
    </div>

    <div id="dialog" class="modal" tabindex="-1" role="dialog">
        <div class="modal-dialog" role="document">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title">系統訊息</h5>
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                <span aria-hidden="true">&times;</span>
              </button>
                </div>
                <div class="modal-body">
                    <p id="message">要顯示的訊息</p>
                </div>
                <div class="modal-footer">
                    <button type="button" class="btn btn-secondary" data-dismiss="modal">關閉</button>
                </div>
            </div>
        </div>
    </div>

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.0/jquery.min.js"></script>
    <!-- <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script> -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>

    <script src="/index.js"></script>
</body>

</html>
