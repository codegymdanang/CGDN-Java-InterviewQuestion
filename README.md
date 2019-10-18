# Java Interview Questions- Đề Cương chuẩn bị cho phỏng vấn với doanh nghiệp

## Java Core
1. Lập trình hướng đối tượng là gì? <br>
Trả lời: lập trình hướng đối tượng là 1 kỹ thuật lập trình, cho phép lập trình viên trừu tượng hóa các đối tượng thực tế thành các đối tượng trong code. <br>
Ví dụ : Trong thực tế để quản lý 1 khách sạn thì mình có các công việc như quản lý khách tới khách sạn, mình có kế toán để thống kê tài chính, mình có bảo vệ. Như vậy lập trình hướng đối tượng thì trong thực tế có đối tượng khách hàng thì trong lập trình mình cũng có đối tượng khách hàng. Trong thực tế khách hàng có tên , tuổi, địa chỉ thì trong lập trình hướng đối tượng mình cũng có tên tuổi địa chỉ. Hướng đối tượng là ngoài thực tế có cái gì thì mình ánh xạ y chang trong lập trình

2. Các tính chất của lập trình hướng đối tượng trong Java? <br>
https://docs.google.com/presentation/d/1K8f4L0PdSqId76n9ueSDDfRxx9_qQm-AaXs6pCV_yAA/edit?usp=sharing <br>
Trả lời: Có 4 tính chất (tính trừu tượng, tính đóng gói, tính kế thừa, tính đa hình) <br>
+ Cho ví dụ minh hoạ cho mỗi tính chất <br>
  * Ví dụ tính trừa tượng <br>
    Ví dụ khi mình mua hàng online trên mạng như trang lazada, tiki hay amazon. Mình click vào mua sản phẩm sau đó 1 tuần sau     mình nhận được sản phẩm của mình. Trừa tượng ở chổ mình không biết lazada, tiki hay amazon sẽ lấy đơn hàng của mình, đóng    gói ra sao và họ vận chuyển như thế nào qua các thành phố và quốc gia. Mình chỉ biết là khi mình bấm vô nút mua hàng thì      mình sẽ nhận được hàng mà không cần quan tâm họ làm như thế nào đế ship hàng mình về đúng địa chỉ . Trong lập trình cũng      vậy khi mình gọi một phương thức từ một đối tượng mình chỉ quan tâm giá trị cung cấp cho phương thức đó và kết quả của        phương thức đó trả về, mình không biết code thực sự bên trong phương thức đó làm gì<br>

  * Ví dụ tính đa hình <br>
   Ví dụ cũng là phương thức chạy thì con gà chạy bằng 2 chân nhưng con chó chạy bằng 4 chân. Cùng một hành động chạy nhưng ở    những ngữ cảnh khác nhau thì hành động khác nhau <br>
  
  * Ví dụ tính kế thừa <br>
Ví dụ như con kế thừa tài sản của cha. Hoặc ví dụ khác như có lớp Animal có các thuộc tính tên, tuổi , và phương thức di chuyển. Nếu con chó kế thừa Animal thì nó sẽ kế thừa các thuộc tính tên , tuổi , và phương thức của lớp cha Animal. Chúng ta không cần phải khai báo lại biến tên, tuổi trong lớp con chó. <br>
* * Lợi ích của tính kế thừa
  Lớp con (lớp A) có thể tận dụng lại các thuộc tính và phương thức của lớp cha (lớp B) (nghĩa là các thuộc tính và phương       thức của lớp B có thể được tái sử dụng bởi lớp A).
  Lớp A có thể định nghĩa thêm thuộc tính và phương thức mới của riêng nó và có thể định nghĩa lại (hay còn gọi là ghi đè       phương thức, overriding) phương thức được kế thừa từ lớp B cho phù hợp với mục đích của nó.

  * Ví dụ tính đóng gói <br>
Tính đóng gói hay còn goi là che dấu dữ liệu . Đối với những dữ liêu quan trọng chúng ta không muốn cho các lớp khác truy cập và sử dung thì ta hạn chế không cho các lớp khác truy cập vào biến hay phương thức bảo mật

3. Hỏi về collection Framework (Cái này hầu như 100% ở đâu phỏng vấn cũng hỏi)<br>
https://docs.google.com/presentation/d/1AhJ3XlgEFJIJW8ETvummQBoUkxT2_z5NjJ8XvQoJj7M/edit?usp=sharing <br>
3.1 ArrayList là gì ? Khi nào dùng ArrayList <br>
3.2 LinkedList là gì ? Khi nào dùng Linkedlist  <br>
3.2 Vector là gì ? Khi nào dùng Vector?<br>
3.3 Stack là gì ? Khi nào dùng Stack <br>
3.4 Queuu là gì ? Khi nào dùng Queue <br>
3.5 Set là gì ? Khi nào dùng Set <br>
3.6 Map là gì ? Khi nào dùng Map <br>
3.7 Phân biệt TreeSet, HashSet và EnumSet ? Khi nào thì dùng <br>
3.8 Phân biệt ArrayList , Linkedlist và Vector ? Khi nào thì dùn
3.9 Sự khác nhau giữa Set với List <br>
4.10 Sự khác nhau giữa ArrayList và Array<br>
   - Array fix cứng giá trị mảng <br>
   - ArrayList có thể co giản được <br>
+ Sự khác nhau giữa Linkedlist với Arraylist <br>
+ Sự khác nhau của Set và 
http://levunguyen.com/2019/08/05/su-khac-nhau-giua-linkedlist-va-arraylist-trong-java/<br>
+ Vector với Arraylist <br> 
+ HashTable với HashMap<br>
https://viettuts.vn/interview/list-cau-hoi-phong-van-java-collection <br>
3.11 Thuật toán BIG O là gì ? <br>
3.12 Trong khi thao tác với các collection (ArrayList,LinkedList, như insert , remove , finding thì cái nào nhanh hơn , cái nào chậm hơn.

4. Sự khác nhau giữa Hashcode và Equals. <br>
Trả lời: https://stackjava.com/java/hashcode-va-equals-trong-java.html
5. Sự khác nhau giữa override và overload<br>
+ Override : Overriding xuất hiện khi trong class con tồn tại một method được định nghĩa với cùng tên và cùng số lượng tham số với method của class cha <br>
+ Overload : Overloading xuất hiện khi trong một class tồn tại một method được định nghĩa với cùng tên nhưng khác số lượng tham số đầu vào với method của class cha. <br>
6. Generic là gì? Cho ví dụ minh hoạ? Tại sao dùng Generic <br>
https://viettuts.vn/java-new-features/generics-trong-java <br>
7. Immutable là gì? Cách để tạo đối tượng immutable? <br>
Trả lời: https://stackjava.com/java/immuable-la-gi.html <br>

8. Sự khác nhau giữa abstract class và Interface.<br>
Trả lời: http://levunguyen.com/2019/06/18/khac-biet-giua-abstract-va-interface/ <br>

9. Hỏi về thuật toán. <br>
+ Tìm kiếm nhị phân<br>
+ Thuật toán sắp xếp <br>
10. Phân biệt các kiểu dữ liệu trong java. Khác nhau thế nào ?
11. Phân biệt sự khác nhau của các access modifier : private , default , protected , public  <br>
Trả lời : <br>
+ Khi một phương thức hoặc biến được khai báo là public, có nghĩa là tất cả các class khác, kể cả các class không thuộc cùng package đều có thể truy cập <br>
+ Khi một phương thức hoặc biến được khai báo là private nó sẽ không thể truy cập từ class khác, kể cả các class cùng source file hay các class con. <br>
+ Khi một phương thức hoặc biến được khai báo là default thì chỉ có các class thuộc cùng package với nó mới có thể truy cập. <br>
+ Protected modifier khá giống với default modifier, nó hạn chế khả năng truy cập trong cùng 1 package, tuy nhiên với protected modifier thì nó còn cho phép truy cập từ các class con kể cả khi class con không nằm cùng package với class cha. (truy cập theo trường hợp thừa kế) <br>
+ Static : khi mình muốn chia sẽ (dùng chung, và là duy nhất tron cả hệ thống) cái biến đó cho các object khác có thể sử dụng được
+ Final : Khi mình muốn giá trị là hằng số và không thể thay đổi được (Ví dụ final double PI = 3.14)

12. Ngoại lệ (Exception là gì) ?
https://docs.google.com/presentation/d/1gJy6TvLc5RR6Rpx8G2JpEvN2GJejrhKwelRSJnikutg/edit?usp=sharing <br>
Khi chúng ta lập trình thì sẽ có những trường hợp có thể xảy ra lỗi . Ví dụ lấy 1 số nguyên chia cho 0. Khi mình thực thi chương trình thì nó sẽ báo ra lỗi Java.lang.ArithmeticException . Trong lập trình mình có rất nhiều Ngoại lệ . Nếu mình đoán được các ngoại lệ có thể xảy ra thì mình có thể dùng try và catch để xử lý ngoại lệ đó. Ngoại lệ rất nguyên hiểm có thể làm chương trình bị đứng . Bắt được ngoại lệ và giải quyết nó giúp chương trình tiếp tục chạy như bình 
12. Check va Uncheck la gi? 
13. Try/Catch/Finally <br>
14. Phân biệt pass-by-value và pass-by-reference và bộ nhớ máy tính <br>
https://docs.google.com/presentation/d/1swUT9shoRZk9VZy3wuxL98IIfShYt-g-Sf1fyP9rbVI/edit?usp=sharing <br>
- CPU xử lý dữ liệu thông qua địa chỉ bộ nhớ nên thứ được truyền vào hàm luôn luôn là địa chỉ bộ nhớ chứ không phải là giá trị.<br>
- Khi chương trình thực thi, dữ liệu trên RAM có thể được lưu trữ trên stack hoặc heap nhưng việc tham chiếu bằng địa chỉ giữa các biến là như nhau nên để cho đơn giản mình sẽ giả sử chúng chỉ được lưu trữ trên stack. <br>

- Pass by value : nghĩa là mình sẽ clone (tạo ra một giá trị mới bằng cách copy (nhân bản) giá trị gốc) giá trị mới từ giá trị gốc và mình chỉ thao táo với bản copy. Khi chúng ta thay đổi các giá trị của đối tượng copy thì không ảnh hưởng đến giá trị gốc. Pass-by-value được hiểu là khi bạn thay đổi biến trong hàm thì ngoài hàm sẽ không bị ảnh hưởng. Nó giống như bạn copy giá trị của biến vào biến khác rồi truyền vào hàm. <br>
- Pass by reference :  Ngược lại với Pass by value . Giá trị gốc sẽ bị thay đổi
Pass-by-reference là khi bạn thay đổi biến trong hàm cũng làm ngoài hàm bị ảnh hưởng. Nó giống như bạn truyền đúng địa chỉ của biến đó vào hàm. <br>
15. Bộ nhớ máy tính . HEAP và STACK <br>
16. Sự khác nhau giữa Class và Object <br>

## Java Spring
1.Nguyên lý Inversion of Control là gì? <br>
IOC : nguyên lý đảo ngược điều khiển. Chúng ta giao cho framework sử lý. Ví dụ như kết nối database, chúng ta giao cho framwork chịu trách nhiệm và điều kiển. 
http://acegik.net/blog/java/spring/core/tong-quan-ve-ioc-trong-spring.html
https://techblog.vn/inversion-of-control-nguyen-ly-cua-cac-nguyen-ly
<br>
1. IOC Container trong Spring
IoC Container trong Spring chính là lõi của Spring Framework. IoC Container sẽ tạo ra các đối tượng, nối chúng lại với nhau, cấu hình chúng, và quản lý vòng đời của chúng từ khi tạo ra đến khi bị hủy. IoC Container sử dụng DI (Dependency Injection) để quản lý các thành phần tạo nên một ứng dụng. Những đối tượng này được gọi là Spring Bean. IoC Container được cung cấp thông tin từ các tập tin XML hoặc từ Java Annotation <br>
Có hai loại IoC Container, đó là: BeanFactory , ApplicationContext <br>
1. Khái niệm DI (dependency injection)  là gì? Cho ví dụ minh hoạ <br>
2. AOP là gì ? Cho ví dụ minh hoạ <br>
3. SpringBoot làm gì ? <br>
4. Vòng đời của 1 Bean <br>
5. Giải thích @Autowire làm gì ? <br>
6. Giải thích @Controller , @Service , @Repository , @Resfult <br>
7. Giải thích JPA là gì ? <br>
8. Webservice là gì ? <br>
9. Restful Webservice là gì ? <br>
10. Maven dùng để làm gì ? <br>
11. Sự khác nhau giữa Session và Cookie ? <br>
12. Cache nghĩa là gì ? <br>
13. Mô hình MVC là gì ? Giải thích ? <br>
14. Truyền dữ liệu từ Controller tới View thì dùng cái gì ? <br>
15. JWT là gì ?

## HTML
1. HTML là gì ? <br>
Trả lời : HTML viết tắt của Hyper Text Markup Language (ngôn ngữ đánh dấu siêu văn bản). Nó là một ngôn ngữ của World Wide Web. Đây là một ngôn ngữ định dạng văn bản chuẩn được sử dụng để tạo và hiển thị các trang trên Web. <br>
2. Khai báo <!DOCTYPE> trong HTML có tác dụng gì? <br> 
3. Điểm khác biệt giữa “visibility:hidden” và “display:none”? <br>
4. Thẻ “div” và thẻ “span” khác nhau thế nào? <br>
5. Canvas trong HTML 5 là gì? <br>
Trả lời : Canvas là một khoảng trống HTML được sử dụng để vẽ đồ họa.<br>

## Java Script
1. Javascript dùng để làm gì? <br>
Trả lời : javascript là ngôn ngữ lập trình kịch bản hướng đối tượng được phát triển bởi Netscape Communications cho các ứng dụng client/server. Javascript là một ngôn ngữ lập trình thông dịch. JavaScript hiển thị các trang web theo cách tương tác và năng động góp phần tạo nên trang web động. Điều này cho phép các trang bắt các sự kiện, hiện thị các hiệu ứng đặc biệt, tự động tạo nội dung HTML, xác thực dữ liệu, tạo cookie, lấy thông tin trình duyệt của người dùng <br>
2. “this” trong Javascript dùng để làm gì?
## CSS
1. CSS framework là gì? <br>
2. Phân biệt Class và ID như thế nào trong CSS? <br>
Trả lời : ID là duy nhất,
ID hay index (chỉ số) được dùng để xác định một đối tượng duy nhất nào đó. Mỗi đối tượng chỉ có thể có một ID. Mỗi trang chỉ có thể có một đối tượng với một ID nào đó. <br>
Class không duy nhất <br>
Class dùng để chỉ một lớp các đối tượng có chung các thuộc tính. Nhiều đối tượng có thể thuộc trong cùng một class. Nhiều class có thể được áp dụng lên cùng một đối tượng. <br>
Class dùng để chỉ một lớp các đối tượng có chung các thuộc tính. Nhiều đối tượng có thể thuộc trong cùng một class. Nhiều class có thể được áp dụng lên cùng một đối tượng. <br>
3. Phân biệt sự khác nhau của padding và margin <br>
4. Thuộc tính float:left là gì ? <br>
5. Thuộc tính clear:both dùng để làm gì ? <br>
6. Phân biệt position : static , absolute , relative , fixed
https://kipalog.com/posts/Tim-hieu-thuoc-tinh-position-trong-CSS <br>

10. Hỏi về các dự án bạn đã làm, nghiên cứu.<br>
Dự án ở đây là các bài tập lớn bạn đã làm, đồ án tốt nghiệp.
Để tạo ấn tượng tốt bạn nên có 1 số project trên github đối với các bài tập lớn của mình hoặc tham gia viết bài trên một blog nào đó về lập trình.<br>

## Database https://www.softwaretestinghelp.com/database-interview-questions/
1. Database là gì ? <br>
2. Trong database có các mối quan hệ gì ?
   + Quan hệ 1 1 (One-to-one): One table has the relationship with another table having the similar kind of column. Each primary key relates    to only one or no record in the related table.
   + Quan hệ 1 nhiều (One-to-many): One table has a relationship with another table that has primary and foreign key relation. The primary key table contains only one record that relates to none, one or many records in the related table.
   + Quan hệ nhiều nhiều (Many-to-many): Each record in both the tables can relate to many numbers of record in another table.<br>
   
1. SQL là gì? <br>
Trả lời: SQL là viết tắt của cụm từ "Structured Query Language." - ngôn ngữ truy vấn mang tính cấu trúc. Nó được thiết kế để quản lý dữ liệu trong một hệ thống quản lý cơ sở dữ liệu quan hệ (RDBMS). SQL là ngôn ngữ cơ sở dữ liệu, được dùng để tạo, xóa, lấy các hàng và sửa đổi các hàng, … Tất cả hệ quản trị cơ sở dữ liệu (Database Management System - DBMS) như MySQL, Oracle, MS Access, Sybase, Informix, Postgres và SQL Server đều sử dụng SQL như là ngôn ngữ cơ sở dữ liệu chuẩn.<br>

2. Định nghĩa từ khóa "JOIN" và các loại "JOIN" khác nhau? <br>
Trả lời: Từ khóa "JOIN" được sử dụng để lấy dữ liệu từ 2 hay nhiều bảng liên quan. Đây là phép kết hợp các dòng dữ liệu từ nhiều bảng lại với nhau. Khi bạn cần truy vấn các cột dữ liệu từ nhiều bảng khác nhau để trả về trong cùng một tập kết quả, bạn cần dùng từ khóa "JOIN". Các loại JOIN như inner join , outer join : leftjoin , right join and fulljoin <br>

3. Primary key là gì?  <br>
Trả lời: Một PRIMARY KEY- Khóa chính là một trường trong một bảng mà nhận diện một cách duy nhất mỗi hàng/bản ghi trong một bảng dữ liệu. Các PRIMARY KEY phải chứa các giá trị duy nhất, không được sử dụng lại. Một cột là PRIMARY KEY thì không được phép có giá trị NULL. Một bảng chỉ cho phép tối đa một PRIMARY KEY, bao gồm một trường đơn hay nhiều trường. Mỗi bảng đều cần có khóa <br>
 
4. Foreign keys là gì? <br>
Trả lời: FOREIGN KEY - Khóa ngoại là một trường trong bảng cơ sở dữ liệu, đó là khóa chính trong một bảng khác được thêm vào tạo ra sự liên quan giữa hai bảng. Trong bảng, giá trị của FOREIGN KEY có thể chấp nhận giá trị NULL, cũng như các giá trị trùng nhau. <br>
4. Composit key là gì ?
is a form of the candidate key where a set of columns will uniquely identify every row in the table. <br>
5. Unique key là gì?
A Unique key is same as the primary key whose every row data is uniquely identified with a difference of null value i.e. Unique key allows one value as NULL value.
5. CHECK Constraint - Ràng buộc CHECK là gì? <br> 
Trả lời: Một ràng buộc CHECK được sử dụng để giới hạn các giá trị hoặc kiểu của dữ liệu có thể nhập và lưu trữ trong một trường của bản ghi. Nếu bản ghi không đáp ứng được điều kiện này, thì sẽ không được lưu trữ vào trong bảng.<br>

6. STORED PROCEDURE là gì? <br>
Trả lời: STORED PROCEDURE là một tập hợp các câu lệnh SQL dùng để thực thi một nhiệm vụ nhất định. Nó hoạt động giống như một hàm trong các ngôn ngữ lập trình khác. STORED PROCEDURE là một khái niệm khá phổ biến và được hầu hết các hệ quản trị cơ sở dữ liệu (DBMS) hỗ trợ, tuy nhiên không phải tất cả đều hỗ trợ STORED PROCEDURE.<br>

7. NORMALIZATION - Chuẩn hóa dữ liệu là gì? <br>
Trả lời: Quá trình thiết kế bảng để giảm thiểu sự dư thừa số liệu, loại bỏ các thay đổi dữ liệu dị thường (update anomaly, insertion anomaly, deletion anomaly) được gọi là quá trình chuẩn hóa dữ liệu. Để thực hiện quá trình này, chúng ta cần phải chia một cơ sở dữ liệu thành hai hay nhiều bảng và xác định các mối quan hệ giữa chúng.
https://docs.google.com/presentation/d/19Q2DYGId0Ns4OjivpGeA8gFNCHtw_Hg8ADHlr-MqWHA/edit?usp=sharing

<br>

8. TRIGGER là gì? <br> Trả lời: TRIGGER được hiểu đơn giản là một thủ tục (một tập các câu lệnh SQL được lưu trữ trong CSDL) được thực thi từ phía máy chủ cơ sở dữ liệu (CSDL) khi có một sự kiện xảy ra như Update, Insert hay Delete. TRIGGER thường dùng để kiểm ra các ràng buộc toàn vẹn trên CSDL, và chúng được thực thi một cách tự động mà không cần sự can thiệp bằng các thao tác thủ công như kiểm tra dữ liệu, đồng bộ hóa dữ liệu <br>

9. Sự khác nhau giữa các câu lệnh TRUNCATE, DELETE và DROP? <br>
Trả lời:
Lệnh DELETE có tác dụng xóa một số hoặc tất cả các hàng từ một bảng dựa trên những điều kiện được chỉ định. Các bản ghi này cũng có thể được phục hồi lại (Roll back).<br>
Lệnh TRUNCATE xóa toàn bộ các bản ghỉ từ bảng bằng cách phân chia lại bộ nhớ các trang. Xử lý này không thể được phục hồi.<br>
Lệnh DROP xóa hoàn toàn một bảng từ cơ sở dữ liệu.<br>

10. Transaction là gì ? <br>
Sequence of operation performed which changes the consistent state of the database to another is known as the database transaction. After the completion of the transaction, either the successful completion is reflected in the system or the transaction fails and no change is reflected <br>
11. Có bao nhiêu loại câu lệnh SQL được sử dụng many SQL statements are used? 
Câu lệnh SQL được chia ra thành 3 loại DDL , DML và DCL <br>
Data Definition Language (DDL) : Các câu lệnh định nghĩa cấu trúc để lưu trữ dữ liệu. <br>
+ CREATE to create a new table or database.
+ ALTER for alteration.
+ Truncate to delete data from the table.
+ DROP to drop a table.
+ RENAME to rename a table. <br>
Data Manipulation Language (DML): Các câu lệnh thao tác với database<br>
+ INSERT to insert a new row.
+ UPDATE to update an existing row.
+ DELETE to delete a row.
+ MERGE for merging two rows or two tables.<br>
Data Control Language (DCL): Các câu lệnh dùng để quản lý permission trong cơ sở dử liệu<br>
+ COMMIT to permanently save.
+ ROLLBACK to undo the change.
+ SAVEPOINT to save temporarily.<br>
12.Model ERD nghĩa là gì ?
Ans: E-R model is an Entity-Relationship model which defines the conceptual view of the database.

E-R model basically shows the real world entities and their association/relations. Entities here represent the set of attributes in the database.<br>

## Devops 

1. Server nghĩa là gì ?<br>
2. Deploy một ứng dụng spring boot lên server như thế nào ? <br>
3. Jenkins dùng để làm gì ? <br>
4. Sonarque dùng làm gì ? <br>
5. Tomcat dùng làm gì ? <br>

## Good Coding
1. Unit Test là gì ? 
2. Lập trình TDD là như thế nào
3. Sonarque có chức năng làm gì ?
4. Bạn có biết design pattern là làm gì ? https://docs.google.com/presentation/d/1VfKg18KaR_sgct4YJamJLsh86IW44HHdGv1ImhC5-Jo/edit?usp=sharing <br>
Hỏi về các design pattern (1 số design pattern quen thuộc, chọn 1 cái từ category là creation, 1 cái từ structural , 1 cái từ behavior). <br>
+ Factory Pattern <br>
+ Abstract Factory Patter  <br>
+ Builder <br>
+ Singleton <br>
+ Decorator <br>
+ State  <br>
+ Strategy <br>

## Angular 

+ Angular là gì ? <br>
+ Giải thích Scope trong Angular ? <br>
+ Data binding trong angular là gì ? <br>
https://malcoded.com/posts/angular-data-binding/ <br>
+ Directive trong angular là gì > <br>
+ Vòng đời của một component ? https://techblog.vn/lifecycle-hooks-in-angular <br>
+ Rounting là gì ? <br>



## Quản lý công việc

+ Kanban dùng để làm gì ? <br>
+ Nguyên lý hoạt động ra sao <br>


## Hỏi về qui trình Scrum

1. Scrum là gì ? <br>
2. Có bao nhiêu roles trong Scrum <br>
3. Có mấy loại meeting trong scrum ? <br>
4. Planing Pocker dùng để làm gì ? <br>
5. Vì sao nên dùng Scrum ? <br>
6. Product Backlog là gì ? <br>
7. Sprint Backlog là gì ?<br>
8. Sprint Retro dùng để làm gì ? <br>
9. 3 câu hỏi trong daily Scrum là gì ? <br>


## Hỏi về khả năng tự học, tiếp cận/giải quyết vấn đề. <br>

Cái này chủ yếu về cách mà bạn giải quyết vấn đề, tiếp cận cái mới. Thí dụ cách mà bạn search google cũng được đánh giá khá cao.

Ví dụ: nhà tuyển dụng hỏi bạn: “em làm chức năng Login” hết bao lâu thời gian thì đừng trả lời mà phải hỏi lại là chức năng login như nào, áp dụng công nghệ nào, các role, permission ra sao…

Hỏi về những kỹ thuật, ngôn ngữ nào mà bạn tự học, tìm hiểu?

Đặc biệt nếu bạn đọc nhiều sách về lập trình thì sẽ được đánh giá rất cao. Một số sách hay về Java như: Sun Certified Programmer for Java®Platform; Clean Code, Java Effective.
<br>
- Ngoài những cái ở trên Bạn biết những kỹ thuật, công nghệ, framework gì nữa ?




