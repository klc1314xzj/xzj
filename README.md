# xzj
  ### 我们作为软件开发人员，为什么要编写单元测试？
  ### 1.单元测试集中注意力于程序的基本组成部分，首先保证每个单元测试通过，才能使下一步把单元组装成部件并测试其正确性具有基础
  ### 2.单元测试可以平行开展，这样可以使多人同时测试多个单元，提高了测试的效率。
  ### 3.单元的规模和复杂性特点，使单元测试中可以使用包括白盒测试的覆盖分析在内的许多测试技术，能够进行比较充分细致的测试，是整个程序测试满足语句覆盖和分支覆盖要求的基础。
  ### 4.保证你最后的代码修改不会破坏之前代码的功能，让代码维护更容易。由于给代码写很多单元测试，相当于给代码加上了规格说  明书，开发人员通过读单元测试代码也能够帮助开发人员理解现有代码。
  ### 5.具有回归性。自动化的单元测试避免了代码出现回归，编写完成之后，可以随时随地地快速运行测试，而不是将代码部署到设备之后，然后再手动地覆盖各种执行路径，这样的行为效率低下，浪费时间。
  ### 6.优化设计。编写单元测试将使用户从调用者的角度观察、思考，特别是使用TDD驱动开发的开发方式，会让使用者把程序设计成易于调用和可测试，并且解除软件中的耦合。
  ### 7.单元测试的好与坏不仅直接关系到测试成本（因为如果单元测试中易发现的问题拖到后期测试发现，那么其成本将成倍数上升），而且也会直接影响到产品质量，因为可能就是由于代码中的某一个小错误就导致了整个产品的质量降低一个指标，或者导致更严重的后果
'''
int a[] =new int[5];
for(int i=0;i<a.length;i++)
	{
		for(int j=0;j<a.length-i-1;j++)
		{
			if(a[j]>a[j+1])
			{
				int temp = a[j+1];
				a[j+1]=a[j];
				a[j]=temp;
			}
		}
	}
	System.out.print("排序后的数组是：");
	for(int i=0;i<a.length;i++)
		System.out.print(a[i]+"\t");
	}
  
  '''
  #### 测试用例：
  +  (1): 1,2,6,8,7
  +  (2): 11,12,6,8,71
  +  (3): 18,14,6,8,71
  +  (4): 1,14,62,8,71
  ![](https://image.baidu.com/search/detail?ct=503316480&z=0&ipn=d&word=java%E5%86%92%E6%B3%A1%E6%8E%92%E5%BA%8F%E7%9A%84%E6%B5%8B%E8%AF%95%E7%94%A8%E4%BE%8B&step_word=&hs=0&pn=13&spn=0&di=14630&pi=0&rn=1&tn=baiduimagedetail&is=0%2C0&istype=2&ie=utf-8&oe=utf-8&in=&cl=2&lm=-1&st=-1&cs=2092898854%2C2137380722&os=3205612262%2C3465875305&simid=0%2C0&adpicid=0&lpn=0&ln=161&fr=&fmq=1600182333123_R&fm=result&ic=&s=undefined&hd=&latest=&copyright=&se=&sme=&tab=0&width=&height=&face=undefined&ist=&jit=&cg=&bdtype=0&oriquery=&objurl=http%3A%2F%2Fimages2015.cnblogs.com%2Fblog%2F1080934%2F201612%2F1080934-20161223143429292-883708690.png&fromurl=ippr_z2C%24qAzdH3FAzdH3Fooo_z%26e3Bvgks52f_z%26e3Bv54AzdH3FrwgxtgqtAzdH3FrAzdH3Fmd890mb_z%26e3Bip4s&gsm=e&rpstart=0&rpnum=0&islist=&querylist=&force=undefined)
 
  
  
  
  
