5a. go to profile
<img width="1912" height="1079" alt="image" src="https://github.com/user-attachments/assets/b40a4d73-0724-4a6a-bfb3-66a5bef3c39e" />
5b. go to register
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/35028623-d250-4c09-bbae-e49caa7561b3" />
5c. login 
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/5df1e0cb-afa8-406c-9743-92b0d6ad0ff8" />
5d. Go to profile with token
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/517b34ed-1f51-45b1-978f-09a879752933" />

Question: Modify code to make token expried?
Có thể làm token hết hạn bằng cách cấu hình thời gian sống khi tạo. Với JWT thì dùng option expiresIn (ví dụ: jwt.sign(payload, secret, { expiresIn: '1h' }) để hết hạn sau 1 giờ). Với session/cookie thì đặt maxAge trong cấu hình (ví dụ: cookie: { maxAge: 60000 } để hết hạn sau 1 phút).


