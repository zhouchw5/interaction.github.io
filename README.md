# Some Interesting Discussions with My Classmates      

You know that since I was a pupil I have got a habits enjoying the moments when others asked me questions. Because it is the best way to refresh and consolidate what you have learned and excavate something new about guys' thingking patterns.             
               
1. Updated on 13th Feb., 2019: I was not the only isolated guy that thought Dr.Batu had stolen some critical steps in explaining the number 
<a href="https://www.codecogs.com/eqnedit.php?latex=C_{m&plus;c}^m=\binom{m&plus;c}{m}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?C_{m&plus;c}^m=\binom{m&plus;c}{m}" title="C_{m+c}^m=\binom{m+c}{m}" /></a>
 of different types of bins in terms of the small-item cases for Bin Packing. We cannot directly encode the different types of bins to map all these types into <a href="https://www.codecogs.com/eqnedit.php?latex=C_{m&plus;c}^m=\binom{m&plus;c}{m}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?C_{m&plus;c}^m=\binom{m&plus;c}{m}" title="C_{m+c}^m=\binom{m+c}{m}" /></a> 
different formulas. Actually we would have two inequalities for enlarging the formula to reach this upper bound for the number of bin types. After explaining to my good friend Sunayani, I just structure the derivation shown as below:                   

 
                       
                       
                    
2. Updated on 15th Jan., 2019: Today when discussing how to rely on solvable decision problems to solve the original problem, we take the path detection between two vertices in a graph as an example. A decision problem in this example can be notated with the instances (G, u, v, k), with the solution "Yes(1)" if the shortest path from u to v in the graph G has the length less or equal to the integer k, otherwise the solution "No(0)". Actually we have two types of methods, one is to focus on the vertices u and v, the other is to consider the sub-set of the graph iteratively.                
                 
The first method in terms of the vertices selection is that we can find some other vertices as a medium between u and v like we name one of them as r, from u to r we have the decision problem (G, u, r, k1), and from r to v we have the decision problem (G, r, v, k2). If k1+k2!=k, we cab know that the shortest path from u to v would not pass through the vertice r. So after we iterate this process across all the vertices other than u and v, we can figure out the final trajectory of the shortest path.               
                   
The second method is to iteratively find a sub-set of the graph G with substraction of some parts of the graph. With the sub-set we name it as G', we can solve the decision problem again in the sub-graph G' as (G', u, v, k'), to see whether k==k' or not. If MIN{k}<MIN{k'}, we can know that the shortest path would pass through the substraction part. Then with iterating this process substracting a vertice orderly, we can finally figure out the final trajectory as well. But this method would come up with another issue that what if the optimal trajectories are not unique. When MIN{k}==MIN{k'}, both are possible that the substracted vertice can be or be not in one of the shortest path(s).                                   
                    
                    
              
              
3. When finding an optimal strategy in a game theory problem with no pure strategical solution, we can firsty eliminate some combinations of strategies by using the dominance, and then using the graph techniques to figure out the equilibrium point. This process can be related to the linear programming picture where we take the zero dual variables for the undefined/inactive constraints.                      
         
         
4. In one seminar of the Data Analysis and Statistical Methods, some girls just asked me about the times counting and cost counting in the Markovian processes. Their confusion is whether to add the factor "1" in the counting equations. It actually depends on the definitions for the counting variables like t_i or c_i. The most common definition is the t_i representing the counting times of hopping from the xth-state needed to reach the absorbing states when starting from the state i. If x = i, we should add the factor "1" in the beginning of the counting equation, otherwise no need for that. Actually, I have got familiar with these node definitions since I was a pupil, especially in some recursive problems.                          

                   
5. One morning when I immersed myself in computing homework, one guy asked me about a junior mathematical problem and then I just considered this problem kind of relaxing and shared with him my derivations in detail. The first step simply utilised the Lagrange Mean Value Theorem. And then we take the maximum of the derivative to obtain the inequality shown as below:                         
<a href="https://www.codecogs.com/eqnedit.php?latex=\sum_{i}(f\left&space;(&space;t_{i&plus;1}&space;\right&space;)-f\left&space;(&space;t_{i}&space;\right&space;))^2=\sum_{i}\left&space;(&space;t_{i&plus;1}-t_{i}&space;\right&space;)^2&space;[{f}'&space;\left&space;(&space;s_{i}&space;\right&space;)]^2\leq&space;\left&space;(&space;MAX_{s\in&space;[0,T]&space;}{{f}'(s)^2}&space;\right&space;)&space;\sum&space;\left&space;(&space;t_{i&plus;1}-t_{i}&space;\right&space;)^2" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\sum_{i}(f\left&space;(&space;t_{i&plus;1}&space;\right&space;)-f\left&space;(&space;t_{i}&space;\right&space;))^2=\sum_{i}\left&space;(&space;t_{i&plus;1}-t_{i}&space;\right&space;)^2&space;[{f}'&space;\left&space;(&space;s_{i}&space;\right&space;)]^2\leq&space;\left&space;(&space;MAX_{s\in&space;[0,T]&space;}{{f}'(s)^2}&space;\right&space;)&space;\sum&space;\left&space;(&space;t_{i&plus;1}-t_{i}&space;\right&space;)^2" title="\sum_{i}(f\left ( t_{i+1} \right )-f\left ( t_{i} \right ))^2=\sum_{i}\left ( t_{i+1}-t_{i} \right )^2 [{f}' \left ( s_{i} \right )]^2\leq \left ( MAX_{s\in [0,T] }{{f}'(s)^2} \right ) \sum \left ( t_{i+1}-t_{i} \right )^2" /></a>                  
And then we can decompose the quadratic form as                 
<a href="https://www.codecogs.com/eqnedit.php?latex=\left&space;(&space;t_{i&plus;1}-t_{i}&space;\right&space;)^2=\left&space;(&space;t_{i&plus;1}-t_{i}&space;\right&space;)\left&space;(&space;t_{i&plus;1}-t_{i}&space;\right&space;)\leq&space;\left&space;\{&space;MAX_{i}[&space;t_{i&plus;1}-t_{i}]&space;\right&space;\}&space;\left&space;(&space;t_{i&plus;1}-t_{i}&space;\right&space;)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\left&space;(&space;t_{i&plus;1}-t_{i}&space;\right&space;)^2=\left&space;(&space;t_{i&plus;1}-t_{i}&space;\right&space;)\left&space;(&space;t_{i&plus;1}-t_{i}&space;\right&space;)\leq&space;\left&space;\{&space;MAX_{i}[&space;t_{i&plus;1}-t_{i}]&space;\right&space;\}&space;\left&space;(&space;t_{i&plus;1}-t_{i}&space;\right&space;)" title="\left ( t_{i+1}-t_{i} \right )^2=\left ( t_{i+1}-t_{i} \right )\left ( t_{i+1}-t_{i} \right )\leq \left \{ MAX_{i}[ t_{i+1}-t_{i}] \right \} \left ( t_{i+1}-t_{i} \right )" /></a>                 
When we take the summation: <a href="https://www.codecogs.com/eqnedit.php?latex=\left&space;\{&space;MAX_{i}[&space;t_{i&plus;1}-t_{i}]&space;\right&space;\}\sum&space;\left&space;(&space;t_{i&plus;1}-t_{i}&space;\right&space;)=&space;\left&space;\{&space;MAX_{i}[&space;t_{i&plus;1}-t_{i}]&space;\right&space;\}\cdot&space;T" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\left&space;\{&space;MAX_{i}[&space;t_{i&plus;1}-t_{i}]&space;\right&space;\}\sum&space;\left&space;(&space;t_{i&plus;1}-t_{i}&space;\right&space;)=&space;\left&space;\{&space;MAX_{i}[&space;t_{i&plus;1}-t_{i}]&space;\right&space;\}\cdot&space;T" title="\left \{ MAX_{i}[ t_{i+1}-t_{i}] \right \}\sum \left ( t_{i+1}-t_{i} \right )= \left \{ MAX_{i}[ t_{i+1}-t_{i}] \right \}\cdot T" /></a>                      
where <a href="https://www.codecogs.com/eqnedit.php?latex=T=t_{n}-t_{0}=t_{n}-t_{n-1}&plus;t_{n-1}-t_{n-2}&plus;...&plus;t_{2}-t_{1}&plus;t_{1}-t_{0}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?T=t_{n}-t_{0}=t_{n}-t_{n-1}&plus;t_{n-1}-t_{n-2}&plus;...&plus;t_{2}-t_{1}&plus;t_{1}-t_{0}" title="T=t_{n}-t_{0}=t_{n}-t_{n-1}+t_{n-1}-t_{n-2}+...+t_{2}-t_{1}+t_{1}-t_{0}" /></a>                 
So finally we obtain <a href="https://www.codecogs.com/eqnedit.php?latex=\sum_{i}(f\left&space;(&space;t_{i&plus;1}&space;\right&space;)-f\left&space;(&space;t_{i}&space;\right&space;))^2&space;\leq&space;\left&space;(&space;MAX_{s\in&space;[0,T]&space;}{{f}'(s)^2}&space;\right&space;)\cdot&space;\left&space;\{&space;MAX_{i}[&space;t_{i&plus;1}-t_{i}]&space;\right&space;\}\cdot&space;T" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\sum_{i}(f\left&space;(&space;t_{i&plus;1}&space;\right&space;)-f\left&space;(&space;t_{i}&space;\right&space;))^2&space;\leq&space;\left&space;(&space;MAX_{s\in&space;[0,T]&space;}{{f}'(s)^2}&space;\right&space;)\cdot&space;\left&space;\{&space;MAX_{i}[&space;t_{i&plus;1}-t_{i}]&space;\right&space;\}\cdot&space;T" title="\sum_{i}(f\left ( t_{i+1} \right )-f\left ( t_{i} \right ))^2 \leq \left ( MAX_{s\in [0,T] }{{f}'(s)^2} \right )\cdot \left \{ MAX_{i}[ t_{i+1}-t_{i}] \right \}\cdot T" /></a>                 
which is exactly the guys felt confused with.               

![chatting](https://github.com/zhouchw5/interaction.github.io/blob/discussion-with-my-classmates/chatting%20record.png)

6. In the first homework for the course Fundemantals of Operations Research & Analytics, a boy asked me how to solve the last question by verifying whether the dual problem of the given infeasible primal is infeasible or unbounded when given some special conditions. I just showed him the equivalence between the undefined/inactive constraints and the corresponding zero dual variables when using the standard form of dual-primal.                              
                       
7. Considering 
<a href="https://www.codecogs.com/eqnedit.php?latex=$J\subset&space;\left&space;\{&space;1,...,p&space;\right&space;\}$" target="_blank"><img src="https://latex.codecogs.com/gif.latex?$J\subset&space;\left&space;\{&space;1,...,p&space;\right&space;\}$" title="$J\subset \left \{ 1,...,p \right \}$" /></a> 
be a subset of indices for the regressors, if we regress y on 
<a href="https://www.codecogs.com/eqnedit.php?latex=$X_{J}$" target="_blank"><img src="https://latex.codecogs.com/gif.latex?$X_{J}$" title="$X_{J}$" /></a> 
only, the residual sum of squares is 
<a href="https://www.codecogs.com/eqnedit.php?latex=$R_{J}=\left&space;\|&space;\widehat{y}\left&space;(&space;J&space;\right&space;)&space;-y\right&space;\|=\sum_{i=1}^{n}\left&space;\{&space;\widehat{y}_{i}\left&space;(&space;J&space;\right&space;)&space;-y_{i}\right&space;\}^2$" target="_blank"><img src="https://latex.codecogs.com/gif.latex?$R_{J}=\left&space;\|&space;\widehat{y}\left&space;(&space;J&space;\right&space;)&space;-y\right&space;\|=\sum_{i=1}^{n}\left&space;\{&space;\widehat{y}_{i}\left&space;(&space;J&space;\right&space;)&space;-y_{i}\right&space;\}^2$" title="$R_{J}=\left \| \widehat{y}\left ( J \right ) -y\right \|=\sum_{i=1}^{n}\left \{ \widehat{y}_{i}\left ( J \right ) -y_{i}\right \}^2$" /></a>. When we add any element in 
<a href="https://www.codecogs.com/eqnedit.php?latex=$\left&space;\{&space;1,..,p&space;\right&space;\}-J$" target="_blank"><img src="https://latex.codecogs.com/gif.latex?$\left&space;\{&space;1,..,p&space;\right&space;\}-J$" title="$\left \{ 1,..,p \right \}-J$" /></a> 
into 
<a href="https://www.codecogs.com/eqnedit.php?latex=$J$" target="_blank"><img src="https://latex.codecogs.com/gif.latex?$J$" title="$J$" /></a>, 
<a href="https://www.codecogs.com/eqnedit.php?latex=$R\left&space;(&space;J&space;\right&space;)$" target="_blank"><img src="https://latex.codecogs.com/gif.latex?$R\left&space;(&space;J&space;\right&space;)$" title="$R\left ( J \right )$" /></a> 
would only decrease (non-increasing). In my opinion it's quite straight forward. When we consider all the variables x, the so-called regressors, the selection of 
<a href="https://www.codecogs.com/eqnedit.php?latex=$\widehat{\beta&space;}$" target="_blank"><img src="https://latex.codecogs.com/gif.latex?$\widehat{\beta&space;}$" title="$\widehat{\beta }$" /></a> 
would minimize the residual sum of the square. Omitting some regressors (only regressing in the sub-set 
<a href="https://www.codecogs.com/eqnedit.php?latex=$\left&space;\{&space;1,...,p&space;\right&space;\}$" target="_blank"><img src="https://latex.codecogs.com/gif.latex?$\left&space;\{&space;1,...,p&space;\right&space;\}$" title="$\left \{ 1,...,p \right \}$" /></a>
) is amount to setting the corresponding coefficients 
<a href="https://www.codecogs.com/eqnedit.php?latex=$\widehat{\beta&space;}_i$" target="_blank"><img src="https://latex.codecogs.com/gif.latex?$\widehat{\beta&space;}_i$" title="$\widehat{\beta }_i$" /></a> 
equal to zero, which is also one of the probable element of the selection set for the original 
<a href="https://www.codecogs.com/eqnedit.php?latex=$\widehat{\beta&space;}$" target="_blank"><img src="https://latex.codecogs.com/gif.latex?$\widehat{\beta&space;}$" title="$\widehat{\beta }$" /></a>. 
And based on the minization optimality, all the probable selections of 
<a href="https://www.codecogs.com/eqnedit.php?latex=$\widehat{\beta&space;}$" target="_blank"><img src="https://latex.codecogs.com/gif.latex?$\widehat{\beta&space;}$" title="$\widehat{\beta }$" /></a> 
would have a residual sum of square greater or equal to that corresponding to the optimal selection of the original 
<a href="https://www.codecogs.com/eqnedit.php?latex=$\widehat{\beta&space;}$" target="_blank"><img src="https://latex.codecogs.com/gif.latex?$\widehat{\beta&space;}$" title="$\widehat{\beta }$" /></a>. That's why the residual sum of square would always decrease when we add more regressors. 




                         
                         
Yours,          
Chuwei Zhou               
2018.12.12               

                          
                          



   
   
