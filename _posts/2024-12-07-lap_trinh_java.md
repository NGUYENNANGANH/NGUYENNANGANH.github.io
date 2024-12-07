---
layout: post
title: Hướng Dẫn Lập Trình Java Cơ Bản
date: 12-08-2024
categories: [programming, Java]
tags: [basic, tutorial]
---

# Hướng Dẫn Lập Trình Java Cơ Bản

## Giới Thiệu

Java là một ngôn ngữ lập trình mạnh mẽ được phát triển bởi Sun Microsystems (nay là Oracle) vào năm 1991. Đặc biệt, Java có triết lý "Write Once, Run Anywhere" (Viết một lần, chạy mọi nơi), cho phép các ứng dụng viết bằng Java có thể chạy trên nhiều nền tảng khác nhau mà không cần thay đổi mã nguồn.

## Cú Pháp Cơ Bản

### 1. Cài Đặt Java

Để bắt đầu lập trình Java, bạn cần cài đặt Java Development Kit (JDK). Bạn có thể tải JDK từ [trang chính của Oracle](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).

### 2. Chương Trình "Hello World"

Chương trình đầu tiên mà ai cũng viết khi học lập trình là "Hello World". Dưới đây là mã nguồn Java đơn giản:
![Desktop View](/post/20241208/image.png){: width="972" height="589" }

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}

