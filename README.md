# Some Interesting Discussions with My Classmates      

You know that since I was a pupil I have got a habits enjoying the moments when others asked me questions. Because it is the best way to refresh and consolidate what you have learned and excavate something new about guys' thingking patterns.        
           
1. When finding an optimal strategy in a game theory problem with no pure strategical solution, we can firsty eliminate some combinations of strategies by using the dominance, and then using the graph techniques to figure out the equilibrium point. This process can be related to the linear programming picture where we take the zero dual variables for the undefined/inactive constraints.             
         
         
2. In one seminar of the Data Analysis and Statistical Methods, some girls just asked me about the times counting and cost counting in the Markovian processes. Their confusion is whether to add the factor "1" in the counting equations. It actually depends on the definitions for the counting variables like t_i or c_i. The most common definition is the t_i representing the counting times of hopping from the xth-state needed to reach the absorbing states when starting from the state i. If x = i, we should add the factor "1" in the beginning of the counting equation, otherwise no need for that. Actually, I have got familiar with these node definitions since I was a pupil, especially in some recursive problems.                          

                   
3. One morning when I immersed myself in computing homework, one guy asked me about a junior mathematical problem and then I just considered this problem kind of relaxing and shared with him my derivations in detail. The first step simply utilised the Lagrange Mean Value Theorem. And then we take the maximum of the derivative to obtain the inequality shown as below:                         
<a href="https://www.codecogs.com/eqnedit.php?latex=\sum_{i}(f\left&space;(&space;t_{i&plus;1}&space;\right&space;)-f\left&space;(&space;t_{i}&space;\right&space;))^2=\sum_{i}\left&space;(&space;t_{i&plus;1}-t_{i}&space;\right&space;)^2&space;[{f}'&space;\left&space;(&space;s_{i}&space;\right&space;)]^2\leq&space;\left&space;(&space;MAX_{s\in&space;[0,T]&space;}{{f}'(s)^2}&space;\right&space;)&space;\sum&space;\left&space;(&space;t_{i&plus;1}-t_{i}&space;\right&space;)^2" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\sum_{i}(f\left&space;(&space;t_{i&plus;1}&space;\right&space;)-f\left&space;(&space;t_{i}&space;\right&space;))^2=\sum_{i}\left&space;(&space;t_{i&plus;1}-t_{i}&space;\right&space;)^2&space;[{f}'&space;\left&space;(&space;s_{i}&space;\right&space;)]^2\leq&space;\left&space;(&space;MAX_{s\in&space;[0,T]&space;}{{f}'(s)^2}&space;\right&space;)&space;\sum&space;\left&space;(&space;t_{i&plus;1}-t_{i}&space;\right&space;)^2" title="\sum_{i}(f\left ( t_{i+1} \right )-f\left ( t_{i} \right ))^2=\sum_{i}\left ( t_{i+1}-t_{i} \right )^2 [{f}' \left ( s_{i} \right )]^2\leq \left ( MAX_{s\in [0,T] }{{f}'(s)^2} \right ) \sum \left ( t_{i+1}-t_{i} \right )^2" /></a>                  
And then we can decompose the quadratic form as                 
<a href="https://www.codecogs.com/eqnedit.php?latex=\left&space;(&space;t_{i&plus;1}-t_{i}&space;\right&space;)^2=\left&space;(&space;t_{i&plus;1}-t_{i}&space;\right&space;)\left&space;(&space;t_{i&plus;1}-t_{i}&space;\right&space;)\leq&space;\left&space;\{&space;MAX_{i}[&space;t_{i&plus;1}-t_{i}]&space;\right&space;\}&space;\left&space;(&space;t_{i&plus;1}-t_{i}&space;\right&space;)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\left&space;(&space;t_{i&plus;1}-t_{i}&space;\right&space;)^2=\left&space;(&space;t_{i&plus;1}-t_{i}&space;\right&space;)\left&space;(&space;t_{i&plus;1}-t_{i}&space;\right&space;)\leq&space;\left&space;\{&space;MAX_{i}[&space;t_{i&plus;1}-t_{i}]&space;\right&space;\}&space;\left&space;(&space;t_{i&plus;1}-t_{i}&space;\right&space;)" title="\left ( t_{i+1}-t_{i} \right )^2=\left ( t_{i+1}-t_{i} \right )\left ( t_{i+1}-t_{i} \right )\leq \left \{ MAX_{i}[ t_{i+1}-t_{i}] \right \} \left ( t_{i+1}-t_{i} \right )" /></a>                 
When we take the summation: <a href="https://www.codecogs.com/eqnedit.php?latex=\left&space;\{&space;MAX_{i}[&space;t_{i&plus;1}-t_{i}]&space;\right&space;\}\sum&space;\left&space;(&space;t_{i&plus;1}-t_{i}&space;\right&space;)=&space;\left&space;\{&space;MAX_{i}[&space;t_{i&plus;1}-t_{i}]&space;\right&space;\}\cdot&space;T" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\left&space;\{&space;MAX_{i}[&space;t_{i&plus;1}-t_{i}]&space;\right&space;\}\sum&space;\left&space;(&space;t_{i&plus;1}-t_{i}&space;\right&space;)=&space;\left&space;\{&space;MAX_{i}[&space;t_{i&plus;1}-t_{i}]&space;\right&space;\}\cdot&space;T" title="\left \{ MAX_{i}[ t_{i+1}-t_{i}] \right \}\sum \left ( t_{i+1}-t_{i} \right )= \left \{ MAX_{i}[ t_{i+1}-t_{i}] \right \}\cdot T" /></a>                      
where <a href="https://www.codecogs.com/eqnedit.php?latex=T=t_{n}-t_{0}=t_{n}-t_{n-1}&plus;t_{n-1}-t_{n-2}&plus;...&plus;t_{2}-t_{1}&plus;t_{1}-t_{0}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?T=t_{n}-t_{0}=t_{n}-t_{n-1}&plus;t_{n-1}-t_{n-2}&plus;...&plus;t_{2}-t_{1}&plus;t_{1}-t_{0}" title="T=t_{n}-t_{0}=t_{n}-t_{n-1}+t_{n-1}-t_{n-2}+...+t_{2}-t_{1}+t_{1}-t_{0}" /></a>                 
So finally we obtain <a href="https://www.codecogs.com/eqnedit.php?latex=\sum_{i}(f\left&space;(&space;t_{i&plus;1}&space;\right&space;)-f\left&space;(&space;t_{i}&space;\right&space;))^2&space;\leq&space;\left&space;(&space;MAX_{s\in&space;[0,T]&space;}{{f}'(s)^2}&space;\right&space;)\cdot&space;\left&space;\{&space;MAX_{i}[&space;t_{i&plus;1}-t_{i}]&space;\right&space;\}\cdot&space;T" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\sum_{i}(f\left&space;(&space;t_{i&plus;1}&space;\right&space;)-f\left&space;(&space;t_{i}&space;\right&space;))^2&space;\leq&space;\left&space;(&space;MAX_{s\in&space;[0,T]&space;}{{f}'(s)^2}&space;\right&space;)\cdot&space;\left&space;\{&space;MAX_{i}[&space;t_{i&plus;1}-t_{i}]&space;\right&space;\}\cdot&space;T" title="\sum_{i}(f\left ( t_{i+1} \right )-f\left ( t_{i} \right ))^2 \leq \left ( MAX_{s\in [0,T] }{{f}'(s)^2} \right )\cdot \left \{ MAX_{i}[ t_{i+1}-t_{i}] \right \}\cdot T" /></a>                 
which is exactly the guys felt confused with.               

![chatting](https://github.com/zhouchw5/interaction.github.io/blob/discussion-with-my-classmates/chatting%20record.png)

4. In the first homework for the course Fundemantals of Operations Research & Analytics, a boy asked me how to solve the last question by verifying whether the dual problem of the given infeasible primal is infeasible or unbounded when given some special conditions. I just showed him the equivalence between the undefined/inactive constraints and the corresponding zero dual variables when using the standard form of dual-primal.                              
                       
5. Considering 
<a href="https://www.codecogs.com/eqnedit.php?latex=$J\subset&space;\left&space;\{&space;1,...,p&space;\right&space;\}$" target="_blank"><img src="https://latex.codecogs.com/gif.latex?$J\subset&space;\left&space;\{&space;1,...,p&space;\right&space;\}$" title="$J\subset \left \{ 1,...,p \right \}$" /></a> 
be a subset of indices for the regressors, if we regress y on 
<a href="https://www.codecogs.com/eqnedit.php?latex=$X_{J}$" target="_blank"><img src="https://latex.codecogs.com/gif.latex?$X_{J}$" title="$X_{J}$" /></a> 
only, the residual sum of squares is 
<a href="https://www.codecogs.com/eqnedit.php?latex=$R_{J}=\left&space;\|&space;\widehat{y}\left&space;(&space;J&space;\right&space;)&space;-y\right&space;\|=\sum_{i=1}^{n}\left&space;\{&space;\widehat{y}_{i}\left&space;(&space;J&space;\right&space;)&space;-y_{i}\right&space;\}^2$" target="_blank"><img src="https://latex.codecogs.com/gif.latex?$R_{J}=\left&space;\|&space;\widehat{y}\left&space;(&space;J&space;\right&space;)&space;-y\right&space;\|=\sum_{i=1}^{n}\left&space;\{&space;\widehat{y}_{i}\left&space;(&space;J&space;\right&space;)&space;-y_{i}\right&space;\}^2$" title="$R_{J}=\left \| \widehat{y}\left ( J \right ) -y\right \|=\sum_{i=1}^{n}\left \{ \widehat{y}_{i}\left ( J \right ) -y_{i}\right \}^2$" /></a>. When we add any element in 
<a href="https://www.codecogs.com/eqnedit.php?latex=$\left&space;\{&space;1,..,p&space;\right&space;\}-J$" target="_blank"><img src="https://latex.codecogs.com/gif.latex?$\left&space;\{&space;1,..,p&space;\right&space;\}-J$" title="$\left \{ 1,..,p \right \}-J$" /></a> 
into 
<a href="https://www.codecogs.com/eqnedit.php?latex=$J$" target="_blank"><img src="https://latex.codecogs.com/gif.latex?$J$" title="$J$" /></a>, 
<a href="https://www.codecogs.com/eqnedit.php?latex=$R\left&space;(&space;J&space;\right&space;)$" target="_blank"><img src="https://latex.codecogs.com/gif.latex?$R\left&space;(&space;J&space;\right&space;)$" title="$R\left ( J \right )$" /></a> 
would only decrease (non-increasing). In my opinion it's quite straight forward. 



                         
                         
Yours,          
Chuwei Zhou               
2018.12.12               

                          
                          



   
   
