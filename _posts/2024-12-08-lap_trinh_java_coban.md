---
layout: post
title: Hướng Dẫn Lập Trình Java Cơ Bản
date: 12-08-2024
categories: [programming, Java]
tags: [basic, tutorial]
comments: true
---

# Lập trình Java

## I. Java cơ bản

### 1. Giới thiệu về Java

- Ngôn ngữ lập trình java được phát triển vào năm 1991 bởi Sun Microsystems (nay là Oracle)
- Tiểu chí phát triển : “Write Once, Run Anywhere” có nghĩa là có nghĩa là “một ứng dụng hoặc mã nguồn khi được viết và biên dịch một lần có thể chạy trên nhiều nền tảng khác nhau mà không cần phải chỉnh sửa hoặc viết lại.”

### 2. Java platform

- 2.1 Java platform - nền tảng Java
    - Được xây dựng để phát triển các ứng dụng và phân phối trển các môi trường đa nền (các hệ điều hành , điện thoại , thiết bị nhúng , enterprise server, …)
    - Sử dụng ngôn ngữ Java (và 1 số ngôn ngữ khác)
- 2.2 Tránh nhầm lẫn với ngôn ngữ java
- 2.3 Các thành phần của Java Platform
    - Các API
        - Java Platform cung cấp các API để lập trình viên không cần sử dụng các API của hệ điều hành
    - Java Virtual Machine (JVM)
        1. Có thể chạy trên software platform khác hoặc trực tiếp trên phần cứng 
        2. Mỗi một platform sử dụng một JVM riêng

### 3. Mô hình biên dịch của java

- 3.1 Mô hình biên dịch của Java platform
    
    Mã nguồn được biên dịch thành Java byte-code , sau đó được thông dịch trên JVM thành các mã lệnh thực thi bởi trình thông dịch Just -In - Time (JIT)
    

### 4. Cú pháp cơ bản

- Là ngôn ngữ phân biệt chữ hoa , chữ thường
- Cú pháp tương tự với C/C++ nhưng vân khác 1 chút

## II. Học cú pháp Java

**Chú ý :**

```java
// Cú pháp psvm + tab
public static void main(String[] args) {
        
    }
```

### 1. Nhập và xuất dữ liệu trong java

---

- 1.1  Xuất dữ liệu trên cùng 1 dòng
    
    ```java
    package finaljava1;
    public class Finaljava1 
    
        public static void main(String[] args) {
            System.out.println("Dong1");
            System.out.println("Dong2");
            System.out.println("Dong3");
        }
    ```
    
    **Kết quả:** 
    
    ![image.png](/post/20241208/anh1.png)
    
    Ngoài ra để xuất cùng 1 giá trị nào đó bạn dùng dấu “+”
    
    ```java
       System.out.println("Dong1"+2);
    ```
    
    **Kết quả :** Dong12
    
- 1.2 Xuất dữ liệu trên cùng dòng
    
    ```java
     System.out.print("Dong1");
     System.out.print("Dong2");
     System.out.print("Dong3");
    ```
    
    **Kết quả :**
    
    ![image.png](/post/20241208/anh2.png)
    
- 1.3 Xuất kí tự đặc biệt
    
    **Thụt vào 1 tab \t**
    **Enter xuống dòng \n**
    **Dấu nháy kép  \”**
    
    ```java
      System.out.println("\tHom nay la thu may");
      System.out.println("Song cau nuoc chay \nCo doi trai gai ngoi ho quan dui");
      System.out.println("Co nguoi n \"Cho di la con mai\"");
    ```
    
    **Kết quả :**
    
    ![image.png](/post/20241208/anh3.png)
    

### 2. Kiểu dữ liệu trong java

---

![image.png](/post/20241208/anh4.png)

***Chú thích:** Wrapper class bạn sử dụng phương thức mà class này cung cấp* 

### 3. Biến

---

- Khái niệm: Là 1 tên gọi của 1 vùng nhớ , để lưu trữ liệu
- Java có 2 kiểu khai báo biến
    - Cho phép thay đổi giá trị
        
        ```java
         // Khai báo biến 
                int a;
                byte tuoi;
                float diemToan;
                //Khai báo nhiều biến cùng kiểu dữ liệu 
                int c,d,e;
            
         //Khởi tạo biến 
                int tuoiCon = 10;
                float dienVan = 7.5f;
                //Chú ý float cần thêm f 
                double diemAnh = 7.5;
                //double không cần thêm f
        ```
        
    - Không cho phép thay đổi giá của 1 biến (Hằng số)
        
        ```java
        //Hằng số thường viết hoa hết 
            final int DOISO = 100;
        ```
        
- Quy tắc đặt tên biến
    
   <aside>
    💡
    
    1. Tên biến chỉ chứa chữ cái (a-z , A-Z) , chứ số (0-9), và dấu gạch chân _ , và dấu $ 
    2. Tên biến không được bắt đầu bằng số 
    3. Tên biến không được trùng với từ khóa và từ dành riêng cho java 
    4. Tên biến phân biệt hoa / thường
    5. Tuân theo quy ước đặt tên biến theo kiểu camelCase : Lạc đà  (chữ cái đầu từ thứ 2 trở đi viết Hoa , còn lại viết thường)
    
    Ví dụ: int tuoiCon = 15;
    
    </aside> 
    

