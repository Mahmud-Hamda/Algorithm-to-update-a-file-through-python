# Algorithm-to-update-a-file-through-python

Let us assume that I am a security professional working at a healthcare company. As part of my job, I am required to regularly update a file that identifies the employees who can access restricted content. The contents of the file are based on who is working with personal patient records. Employees are restricted to access based on their IP address. There is an allow-list for IP addresses permitted to sign into the restricted subnetwork. There is also a remov-list that identifies which employees I must remove from this allow-list.
The "allow_list.txt" file identifies an allow-list of IP addresses. A separate remove-list identifies IP addresses that should no longer have access to this content. The remove-list = ["192.168.97.225", "192.168.158.170", "192.168.201.40", "192.168.58.57"]


My task is to create an algorithm that uses Python code to check whether the allow-list contains any IP addresses identified on the remove-list. If so, I should remove those IP addresses from the file containing the allow-list. So, I created an algorithm to automate updating the "allow_list.txt" file and remove these IP addresses that should no longer have access. I will show it step-by-step as follows.
