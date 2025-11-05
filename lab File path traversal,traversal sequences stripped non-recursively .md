#lab : File path traversal, traversal sequences stripped non-recursively
    
    Use Burp Suite to intercept and modify a request that fetches a product image.

    Modify the filename parameter, giving it the value:
    ....//....//....//etc/passwd
    Observe that the response contains the contents of the /etc/passwd file.


![payload](i6.png)

##result

![result](i7.png)
![result](i8.png)

