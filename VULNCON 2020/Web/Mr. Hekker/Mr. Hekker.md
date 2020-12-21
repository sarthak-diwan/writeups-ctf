# XXE
##### URL:  [Link](http://hekker.noobarmy.org/ "Mr. Hekker")

* This was the form present in homepage.
![img1](img1.png)
* The POST request being sent:
![img2](img2.png)
* Response:
![img3](img3.png)

+ ##### We can try XML external entity (XXE) injection.
![img4](img4.png)
This confirms the _vulnerability_.

+ Now we can get the flag at */home/hekker/flag.txt*
			_vulncon{MR_H4kk3r_w1th_XXE_(+_+)}_