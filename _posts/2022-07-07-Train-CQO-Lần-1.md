## Training coder Quốc Oai lần thứ nhất
### Dạng 1: số nhị phân 
**Ví dụ câu 3 đề minh hoạ**:
```python=
a,b = map(int,input().split())
n = int(input())
d = b -a
an = a + (n -1)*d
snp = bin(an)

snp = str(snp)
if snp[0]=="-": print('-',end='')
for i in range(len(snp) -1, -1, -1):
    if(snp[i] !='1' and snp[i]!='0'): break;
    else: print(snp[i],end= '')
```

```
for i in range(len(snp) -1, -1, -1): trong python = 
với for(int i = snp.length()-1; i >= 0; i --) trong c++

```
### Công thức:
$$
A_k = A_1 + (k - 1)*d
$$
***Với d là khoảng cách giữa 2 số liên tiếp***
sau khi đã có mực nước biển năm thứ n 
chúng ta sẽ chuyển nó sang sâu nhị phân 
sau khi đã có sâu nhị phân thì chúng ta xuât ngược lại là xong

[Cách chuyển đổi số thập phân sang nhị phân ](https://www.engisv.info/?p=220#:~:text=%C4%90%E1%BB%83%20%C4%91%E1%BB%95i%20m%E1%BB%99t%20s%E1%BB%91%20th%E1%BA%ADp,theo%20m%C5%A9i%20t%C3%AAn%20m%C3%A0u%20xanh).

## chua de minh hoa
Bài 1:
dễ dàng thấy được số đẹp thứ n là số thứ n nhân với 18:
full code python
```python=
n = int(input())
print(n*18)
```
Bài 2:
python code python:
```python=

```
 Phương pháp quy hoạc độn
 số fibo là số bắt đầu bằng số 0 1 1 2 3 
```python=
def fibo(n):
    if n == 0: return 0
    if n == 1:
        return 1
    return fibo(n - 1) + fibo(n - 2 )
```
phuowng phaps dder luwu luưa tất cả các trường đã tính để tính lại giảm thời ian chạy code
```python=
n = int(input())
n=[];
for i in range(n+ 1000):
    n.append(0);
n[1] = 0
n[2] = 1;
for i in range(3,n + 1 ):
    n[i] = n[i - 1] + n[i - 2];
```
> []
---
full code bài 1 2 3 4 5 và bài minh hoạ sẽ đc up sau 

