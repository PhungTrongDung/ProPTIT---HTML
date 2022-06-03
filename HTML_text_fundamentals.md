http://127.0.0.1:5500/C++/VS_Code/Proptit_HTML/HTML_text_fundamentals.html

        
                                                    HTML text fundamentals
     
        I. Thẻ h1 -> h6:
            - Trong một trang HTML có thể phân chia ra thành nhiều đề mục với các cấp độ khác nhau. Có 
            6 cấp độ tương ứng với các  thẻ từ <h1> đến <h6> (<h1> là thẻ có cấp độ cao nhất và giảm dần
            về <h6>)
            - Khi sử dụng cần sử dụng theo đúng cấp độ của đề mục - không bỏ qua đề mục ( ví dụ có <h3>
            nhưng không có <h2>). 
            - Trong 1 trang chỉ dùng 1 thẻ <h1>.
     
         
            <h1>Nhập môn Web: Các kiến thức cơ bản về HTML</h1>
            <h2>Nhập môn Web: Các kiến thức cơ bản về HTML</h2>
            <h3>Nhập môn Web: Các kiến thức cơ bản về HTML</h3>
            <h4>Nhập môn Web: Các kiến thức cơ bản về HTML</h4>
            <h5>Nhập môn Web: Các kiến thức cơ bản về HTML</h5>
            <h6>Nhập môn Web: Các kiến thức cơ bản về HTML</h6>
            
        ---------------------------------------------------------------------------------------------------  
         
        * Thẻ <hr>:  được dùng để xác định sự thay đổi chủ đề/đề mục trong 1 trang HTML
        <hr>
        
        <h1>WhileD</h1>
        
        ---------------------------------------------------------------------------------------------------
        
        II. Thẻ p (paragraphs)
            - Thẻ <p> tạo ra một đoạn văn bản. 
            - Sử dụng thẻ <p> với nội dung văn bản nằm giữa mở thẻ <p> và đóng thẻ </p>.
            - Với thẻ <p>, trình duyệt tạp ra 1 khối để hiển thị nội dung văn bản, khối nay phân cách bởi
            các dòng trống.
            - 

         <p>
            * Thẻ <br>: thẻ xuống dòng
            
            Vì chẳng thể nào biết trước <br>
            Ở kiếp sau ta còn có thể gặp lại nhau?
            Vậy nên anh vẫn mãi nỗ lực, và dành hết bao điều tốt đẹp nhất đến em
            Nhưng vô tình khiến em tổn thương nhiều
            Tình mình bỗng nhiên trở nên bế tắc!
            Chẳng phải cố ý, chỉ là vì yêu em!

        </p>

        --------------------------------------------------------------------------------------------------

        III. Thẻ <ol> và <ul>
                + Sử dụng thẻ <ol> tạo danh sách có thứ tự và thẻ <ul> tạo danh sách không có
                thứ tự trong HTML, mỗi phần tử trong danh sách là <li>, thiết lập kiểu hiển thị
                danh sách với thuộc tính type của <ol> và <ul>
            - Thẻ <ol> (ordered list): tạo danh sách có thứ tụ
                + Danh sách có thứ tự là loại danh sách mà "chỉ mục" của các danh mục trong danh
                sách sẽ có thứ tự.
                + 
            - Thẻ <ul> (unordered list): tạo ds không có thứ tự
                + Danh sách không có thứ tự là loại danh sách mà "chỉ mục" của các danh mục trong 
                danh sách đều có chung một kiểu.


        <ol>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
            <li>SQL</li>
        </ol>

        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
            <li>SQL</li>
        </ul>

        --------------------------------------------------------------------------------------------------

            1. Thẻ <ol>:
                - Thuộc tính của thẻ <ol>: có 3 thuộc tính thường hay sử dụng nhất.
                    + type: xác định "kiểu chỉ mục" cho các danh mục trong danh sách
                        . type có 5 giá trị cơ bản: 1, a, A, i, I

                        <ol type="....">
                            <li> HTML </li>
                            ......
                        </ol>

                        * NOTE: Ngoài việc sử dụng thuộc tính type của thẻ <ol> để xác
                                định kiểu chỉ mục cho các danh mục trong danh sách thì 
                                chúng ta cũng có thể dùng thuộc tính list-style-type 
                                trong CSS để thay thế.
                                . decimal: 1
                                . lower-alpha: a
                                . upper-alpha: A
                                . lower-roman: i
                                . upper-roman: I
                        
                        <!-- list-style-type -->
                        Ví dụ thuộc tính list-style-type trong CSS
                        * Với ol
                        <ol style="list-style-type:upper-alpha">
                            <li>HTML</li>
                            <li>.......</li>
                        </ol>

                        * Với ul
                        <ul style="list-style-type:decimal">
                            <li>HTML</li>
                            <li>CSS</li>
                        </ul>
                        

                        <!-- type -->
                        - Ví dụ thuộc tính type
                        <ol type="1">
                            <li>HTML</li>
                            <li>.......</li>
                        </ol>
                    
                    
                    + reversed: đảo ngược thứ tự chỉ mục của các danh mục trong danh sách
                    
                        <!-- reversed -->
                        - Ví dụ reversed
                        <ol reversed type="i">
                            <li>HTML</li>
                            <li>CSS</li>
                            <li>JavaScript</li>
                        </ol>
        
                    + start: Xác định "thứ tự bắt đầu" của chỉ mục của danh mục đầu tiên trong danh sách
                    
                        <!-- start -->
                        - Ví dụ start
                        <ol type="i" start="3">
                            <li>HTML</li>
                            <li>CSS</li>
                            <li>SQL</li>
                        </ol>
            
            2. Thẻ <ul>:
                - Thuộc tính type của thẻ ul: có 3 giá trị: 
                    + disc (mặc định)
                    
                        - Ví dụ về kiểu disc của thuộc tính type
                        <ul >
                            <li>HTML</li>
                            <li>CSS</li>
                            <li>MySQL</li>
                        </ul>
                    
                    + circle 
                        
                        - Ví dụ về kiểu circle của thuộc tính type
                        <ul type="circle">
                            <li>HTML</li>
                            <li>CSS</li>
                            <li>MySQL</li>
                        </ul>
                    
                    + square
                        
                        <p>Ví dụ về kiểu disc của thuộc tính type</p>
                        <ul type="square">
                            <li>HTML</li>
                            <li>CSS</li>
                            <li>MySQL</li>
                        </ul>


            3. Thẻ <li>
            - Ví dụ thẻ li
            <ul>
                <li><b><i>HTML</i></b></li>
                <li type="a">CSS</li>
                <li>JavaScript</li>
                <li>MySQL</li>
                <li type="1">PHP</li>
                <li>jQuery</li>
                <li type="circle">Codeigniter</li>
             </ul>

