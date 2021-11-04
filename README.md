<!DOCTYPE html>

<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8"/> 
    <meta name ="viewport" content="width=device-width,initial-scale=1"/>
    <style> 
        #exercises
        {
            font-size:24px;
            font-family: Arial, Helvetica, sans-serif;
            background-color:indianred;
        }
    </style>
</head>

<body>
    <title>
        Topic 1
    </title>
    <h1> Vẽ lưu đồ thuật toán </h1>
    <span>
        <p style="color:blue;font-size:20px;font-family:Arial;font-size:30px;">Thư mục chứa đề tại
        <a href="https://drive.google.com/drive/folders/1-huEQhc7c4zG3i7XNkEUlXylODyWNHL7" target="_blank" style="text-decoration: none;color:red;font-size: 25px;"> đây </a>
        </p>
    </span>
    <p style="color:peru;font-weight: bold;font-size:28px;"> Bài 1 </p>
    <div>
        <h1 id="exercises">
            <p>
                Phân tích:x<sup>11</sup>=(x.x).(x.x).(x.x).(x.x).(x.x).x=(x<sup>2</sup>.x<sup>2</sup>).(x<sup>2</sup>.x<sup>2</sup>).x<sup>2</sup>.x=x<sup>4</sup>.x<sup>4</sup>.x<sup>2</sup>.x
            </p>  
            <p>
                <p> x<sup>2</sup>=x.x -> 1 phép nhân </p>
                <p> x<sup>4</sup>=x<sup>2</sup>.x<sup>2</sup> -> 2.2 phép nhân </p>
            </p>
        </h1>
    </div>
    <p style="color:peru;font-weight: bold;font-size:28px;"> Bài 2 </p>
    <div>
        <h1 id="exercises">
            <p style="font-family: Verdana, Geneva, Tahoma, sans-serif;">
                Tính tổng các chữ số: lấy tổng các kết quả n lấy phần dư cho 10,n chia cho 10 -> Sử dụng vòng lặp. Lặp đến khi nào n=0
            </p>  
        </h1>
    </div>
    <p style="color:peru;font-weight: bold;font-size:28px;"> Bài 3 </p>
    <div>
        <h1 id="exercises">
          
            <p><sup>x<sub>i</sub></sup>&frasl;<sub>(1+...+i)</sub> </p>
                
                <p>- Sử dụng vòng lặp để tính </p>
                <p>- Dùng 2 biến để tính tử và mẫu: tu*=x,mau+=i </p>
            </p>  
        </h1>
    </div>
    <p style="color:peru;font-weight: bold;font-size:28px;"> Bài 4 </p>
    <div>
        <h1 id="exercises">
          
                <span> Dạng tổng quát: tại thời điểm i, biểu thức có dạng: (-1)<sup>i</sup>.x<sup>2i</sup> </span>
                <p>- Sử dụng vòng lặp để tính </p>
                <p>- Dùng 2 biến để tính giá trị (-1)<sup>i</sup> và giá trị x<sup>2i</sup> tại thời điểm i </p>
            </p>  
        </h1>
    </div>
    <p style="color:peru;font-weight: bold;font-size:28px;"> Bài 5 </p>
    <div>
        <h1 id="exercises">
          
                <span> Thử chạy tay với biến x và n đủ nhỏ để tìm thuật toán phù hợp, chạy từ ở trong ra </span>
                <p>- Sử dụng vòng lặp để tính </p>
                <p>- Tại thời điểm i: sqrt(x<sup>i</sup>+sqrt(x<sup>i-1</sup>+sqrt(..+sqrt(x))))  </p>
                <p>- Dùng 2 biến để tính giá trị x và tổng giá trị căn tại thời điểm i</p>
            </p>  
        </h1>
    </div>
    <p style="color:peru;font-weight: bold;font-size:28px;"> Bài 6 </p>
    <div>
        <h1 id="exercises">
        
                <p>- Lần 1: tính tổng 1/n và dùng setprecision(6) -> sai </p>
                <p>- Lần 2: Lặp đến khi nào sum=1+<sup>1</sup>&frasl;<sub>2</sub>+<sup>1</sup>&frasl;<sub>3</sub>+...+<sup>1</sup>&frasl;<sub>n</sub> có độ chính xác 10<sup>-6</sup>  </p>                
            </p>  
        </h1>
    </div>
    <p style="color:peru;font-weight: bold;font-size:28px;"> Bài 7 </p>
    <div>
        <h1 id="exercises">
        
                <span> Dạng tổng quát: tại thời điểm i (i>1), biểu thức có dạng: a<sub>n</sub>=5.a<sub>i-1</sub>+2.3<sup>i</sup>-6.7<sup>i</sup>+12</span>
                <p> - Khởi tạo a<sub>1</sub>=-2 </p>
                <p>- Sử dụng vòng lặp để tính </p>
                <p>- Sử dụng 3 biến để tính (tại thời điểm i): 5.a<sub>i-1</sub>,2.3<sup>i</sup>,-6.7<sup>i</sup>+12</p>
            </p>  
        </h1>
    </div>
    <p style="color:peru;font-weight: bold;font-size:28px;"> Bài 8 </p>
    <div>
        <h1 id="exercises">
        
                <p> Đầu vào quy định x,y,z đã là 3 cạnh tam giác nên không cần kiểm tra có phải 3 cạnh hay không </p>
                <p> Sử dụng tính chất về cạnh để phân loại tam giác </p>
                <ol>
                    <li> Pytago: tam giác vuông </li>
                    <li> Hai cạnh bằng nhau: tam giác cân </li>
                    <li> Ba cạnh bằng nhau: tam giác đều </li>
                    <li> Bình phương cạnh huyền lớn hơn tổng bình phương 2 cạnh còn lại: tam giác tù </li>
                    <li> Còn lại sẽ là tam giác nhọn </li>
                </ol>
            </p>  
        </h1>
    </div>
    <p style="color:peru;font-weight: bold;font-size:28px;"> Bài 9 </p>
    <div>
        <h1 id="exercises">
        
                <p>- Trong khi code, có thể dùng sqrt() và ép kiểu về int </p>
                <span>- Kiểm tra tích sqrt() có bằng n hay không( dựa vào tính chất số chính phương) hoặc ta có thể dùng vòng for từ 1 đến n/2 để kiểm tra,nếu i.i = n thì n là số chính phương còn nếu vòng lặp không số nào thỏa thì n không phải số chính phương</span>
            </p>  
        </h1>
    </div>
    <p style="color:peru;font-weight: bold;font-size:28px;"> Bài 10 </p>
    <div>
        <h1 id="exercises">
        
                <span> N có dạng 5<sub>m</sub>(m>=0) là N chia hết cho 5, ta chỉ cần N/5 đến khi nào N<span data-entity="&amp;lt;" data-code="&amp;#60;" data-unicode="\003C" data-hex="&amp;#x3c;" data-css="\3C ">
                        &lt;            </span>5 và xem khi N<span data-entity="&amp;lt;" data-code="&amp;#60;" data-unicode="\003C" data-hex="&amp;#x3c;" data-css="\3C ">
                        &lt;            </span>5 có dư hay không
</span>5 có dư hay không </span>
                <p>Nếu dư thì N không phải dạng 5<sup>m</sup> Ngược lại thì N là dạng 5<sup>m</sup> </p>
            </p>  
        </h1>
    </div>
</body>

</html>
