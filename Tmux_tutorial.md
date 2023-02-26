1. Để bắt đầu sử dụng Tmux ta dùng lệnh:
```
$ tmux
```
2. Thoát khỏi Tmux ta dùng lệnh:
```
$ exit
```
3. Để liệt kê các session hiện có ta dùng lệnh:
```
$ tmux ls
```
4. Để truy cập nhanh session gần nhất ta dùng lệnh:
```
$ tmux a
```
5. Để truy cập session được chỉ định ta dùng lệnh:
```
$ tmux a -t <name_session>
```
6. Để tạo 1 session mới ta dùng lệnh:
```
$ tmux new -s <name_session>
```
7. Để xóa (kill) 1 session bất kì ta dùng lệnh: 
```
$ tmux kill-session -t <name_session>
```
8. Để xóa tất cả session hiện có trên máy ta dùng lệnh:
`$ pkill -f tmux` 
hoặc
`$ tmux kill-server`

