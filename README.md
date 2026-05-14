📊 Adidas Product & Inventory Analysis (BR Market)
📝 პროექტის მიმოხილვა
პროექტი მიზნად ისახავს ბრაზილიის ბაზარზე არსებული Adidas-ის პროდუქციის კომპლექსურ ანალიზს. მონაცემების დამუშავება მოხდა SQL-ის გამოყენებით, ხოლო ვიზუალიზაცია და ბიზნეს-ინსაიტების გენერირება — Power BI-ში.

🛠 ტექნიკური ნაწილი (SQL)
მონაცემების დამუშავებისას გამოყენებულია SQL-ის შემდეგი "Advanced" ტექნიკები:

Data Cleaning: დუბლიკატების ფილტრაცია ROW_NUMBER() ფუნქციით და არასრულყოფილი ჩანაწერების (Missing prices, invalid sizes) გასუფთავება.
Business Logic: ფასნამატის (Markup), მოგების მარჟისა და ფულადი სხვაობის (Difference in Value) გამოთვლა რთული მათემატიკური ფორმულებით.
Segmentation: პროდუქტების დაყოფა საფასო კატეგორიებად (Budget, Mid-Range, Premium) და ფასდაკლების ინტენსივობის მიხედვით.
Inventory Analysis: "Stock Fill Rate"-ის გამოთვლა, რაც აჩვენებს ხელმისაწვდომი ზომების წილს თითოეული კატეგორიისთვის.

📈 ვიზუალიზაცია (Power BI)
Power BI რეპორტში რეალიზებულია:
Dynamic KPIs: გაყიდვების ფასისა და თვითღირებულების შედარებითი ანალიზი.
Assortment Health: ზომების ხელმისაწვდომობის ინტერაქტიული მატრიცა, რომელიც აჩვენებს "Out of Stock" პრობლემებს.
Price Strategy Analysis: ფასდაკლებების გავლენა სხვადასხვა საფასო სეგმენტზე.
DAX Measures: გამოყენებულია DAX ფუნქციები საშუალო რეიტინგების, გაყიდვების წილისა და ფასების ვარიაციულობის დასათვლელად.



ანალიზმა აჩვენა კავშირი პროდუქტის რეიტინგსა და მის საფასო სეგმენტს შორის.
<img width="878" height="484" alt="adidas1" src="https://github.com/user-attachments/assets/cd67f126-fd78-43c3-8a38-fc76f5ee908e" />
<img width="874" height="489" alt="adidas2" src="https://github.com/user-attachments/assets/d31d0d9e-cf60-4422-a230-52b66af39d84" />
<img width="873" height="487" alt="adidas3" src="https://github.com/user-attachments/assets/723360a2-9def-4980-9653-c6028535281a" />
<img width="874" height="485" alt="adidas4" src="https://github.com/user-attachments/assets/638fdbde-4f48-40ac-9329-6735ebe3d0fd" />
<img width="875" height="483" alt="adidass5" src="https://github.com/user-attachments/assets/2ada3335-7345-4cc4-bd49-6ff9ff0bef10" />


<img width="957" height="163" alt="ag2" src="https://github.com/user-attachments/assets/a4633ec4-3ec8-4cb3-91ee-5a9c7a8ec732" />
<img width="993" height="231" alt="ag1" src="https://github.com/user-attachments/assets/f52ef02e-7327-48e4-ae6d-15a6281d41d3" />
<img width="992" height="135" alt="ag3" src="https://github.com/user-attachments/assets/59fb5e18-5411-4bb0-b2f9-45eb9ee10890" />
<img width="996" height="283" alt="ag4" src="https://github.com/user-attachments/assets/7c3fd6d9-2281-4523-bddf-b27c4e6e5584" />
<img width="985" height="144" alt="ag5" src="https://github.com/user-attachments/assets/719936e3-0299-49e6-9bae-8806120a16e1" />
<img width="995" height="263" alt="ag6" src="https://github.com/user-attachments/assets/87de2b5f-c73b-43c9-b1d4-7d23b6d94751" />
<img width="976" height="424" alt="ag7" src="https://github.com/user-attachments/assets/6518705d-8b6f-4e2b-aba4-b546e1855dc8" />


