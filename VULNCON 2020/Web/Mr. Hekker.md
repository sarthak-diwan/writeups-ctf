# XXE
##### URL:  [Link](http://hekker.noobarmy.org/ "Mr. Hekker")

* This was the form present in homepage.
![[Pasted image 20201221133843.png]]
* The POST request being sent:
![[Pasted image 20201221134134.png]]
* Response:
![[Pasted image 20201221134216.png]]

+ ##### We can try XML external entity (XXE) injection.
![[Pasted image 20201221134742.png]]
This confirms the _vulnerability_.

+ Now we can get the flag at */home/hekker/flag.txt*
			_vulncon{MR_H4kk3r_w1th_XXE_(+_+)}_