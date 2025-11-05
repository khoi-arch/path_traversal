#lab : File path traversal, traversal sequences blocked with absolute path bypass

    
    Use Burp Suite to intercept and modify a request that fetches a product image.
    Modify the filename parameter, giving it the value /etc/passwd.
    Observe that the response contains the contents of the /etc/passwd file.



![payload](i4.png)

##result

![result](i3.png)
![result](i5.png)

