#lab : File path traversal, simple case 

    Use Burp Suite to intercept and modify a request that fetches a product image.

    Modify the filename parameter, giving it the value:
    ../../../etc/passwd
    Observe that the response contains the contents of the /etc/passwd file.

![payload](i0.png)

##result
![payload](i1.png)
![result](i2.png)

