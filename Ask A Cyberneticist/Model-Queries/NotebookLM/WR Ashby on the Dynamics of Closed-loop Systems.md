## How would W.R. Ashby describe closed-loop feedback?

W.R. Ashby <sup>1</sup> would describe closed-loop feedback primarily as a state of effective two-way interaction between components within a system. He defines feedback as being present if we can find two variables that are each dependent on the other <sup>2</sup>. This interaction forms a circuit where the behaviour of one part is influenced by the other, and this influence eventually returns to the first part <sup>2</sup>.    

__Ashby identifies several key characteristics and insights regarding closed-loop feedback:__     
Feedback as a "Closing Link": Drawing on the theory of servomechanisms, he notes that a human operator can be considered part of a control system, acting as the "closing link" <sup>3</sup> that takes account of the difference between actual output and desired output to alter the input.     

__The Necessity for Oscillation:__    
Ashby posits that if the variables of an absolute system undergo a recurring cycle of behaviour, feedback must be present <sup>2,4</sup>. He argues that variables cannot be interconnected in a way that produces oscillation without forming a circuit <sup>4</sup>.    

__Feedback and Goal-Seeking:__ While many associate feedback with purposive behavior, Ashby argues that goal-seeking behaviour does not necessarily imply feedback; simple systems without feedback can still return to a central state when displaced <sup>5,6</sup>. However, a powerful-acting servo-mechanism utilizing feedback can add a "powerful stabilising effect," making a machine more irresistible to opposition and ensuring it converges to zero error more rapidly <sup>5,6,8</sup>.    

__Critique of "Negative Feedback":__ Ashby considers the concept of "negative feedback" to be too limited and simple to serve as a fundamental concept in general systems <sup>9,10</sup>. He demonstrates that it is algebraically possible for positive feedback to result in stability and for negative feedback to result in instability, depending on the values of the coefficients within the system's matrix <sup>10-12</sup>.     

__Feedback as a Selective Change Mechanism:__ In his theory of the ultrastable system, feedback is the mechanism by which the system perceives "pain" or a threat to its essential variables <sup>13,14</sup>. This feedback loop informs the system that its current internal organization is failing to maintain stability, thereby triggering a "reset" or change in step-functions until a new, stable equilibrium is found <sup>15,16</sup>.     

__Feedback through the Environment:__ Ashby emphasizes that a complete dynamic system often includes the environment as a feedback link <sup>17,18</sup>. For instance, a person driving a car is part of a functional loop where their actions affect the environment (the car's position), and the environmental feedback (visual signals from the road) travels back through the driver's brain to correct the initial movement <sup>18,19</sup>.    

Ultimately, Ashby views simple feedback as a subset of more complex reacting circuits <sup>20</sup>. He notes that for a part of a system to behave with more stability than it possesses intrinsically, feedback is a necessary condition <sup>1</sup>.     

__Footnotes__      
<sup>1</sup> From transcription of Ashby's notebook from 1948-1949        
(232/277) 2656 [Matrix]=0 So the latent roots of [A] will be included among those of the whole. Therefore not all elements of C can be zero. Similarly it can be proved that not all elements of B can be zero. Consequently, a non-zero feedback must...  What has been shown is (a) that if A-> D, then A's latent roots are not altered -which is obvious anyway, and (b) that if D->A, A's latent roots are still unaltered -which is by no means obvious. A's roots can be altered only if there is effective two-way interaction. Gremlin or no, there must still be feedback. Summary: If a part is to behave with more stability than it has intrinsically, then feedback is necessary.

<sup>2</sup> From transcription of Ashby's notebook from 1948-1949        
(182/277) 2606 i.e. an integrating delay with a positive feedback of a (negative if a is negative). (Note that an adds on to the input [Figure]). Summary: Transfer function of a single variable..... 15 July '49 Theorem: If the variables of an absolute system go through a recurring cycle of behaviour, then feedback must be present. Definition: "Feedback" is present if we can find two variables each of which is dependent on the other. In the n-space, the path of the representative point must be closed loop. Select, otherwise arbitrarily, a state A on the path such that no variable is stationary. If A's coordinates are X1,...,Xn, draw through A the planes x1=X1, ..., xn=Xn. First takes the plane x1=X1. As the path, in passing A, goes from one side of the plane to the other, eventually it must recross the plane at least once to form the closed....

<sup>3</sup> From transcription of Ashby's notebook from 1948-1949        
16 Dec '47 In writing up my book I came to "change of set" & used Lubbock's work (p.1735). This raised the awkward point that certain variables which don't vary can be treated indifferently as (58/184) 2306....          

parameters or variables - a most awkward feature when I am trying to emphasize that they are utterly different. But I suddenly realized that a possible way, that needs working over, is to drop the whole concept of a para-
& then to enquire into the special features which occur when some of them are null-variables, or non-varying variables. In the equations it simply means that we can have x1=fi(x,[Figure]) with [Figure] as parameter, or we can take [Figure] into the system and write [Equations] The factual content in the same so long as we leave the system alone for the arbitrary value of [Figure] in the first is merely [Figure]^0 in the second. The gain in physical reality is (59/184) 2307....

<sup>4</sup> From transcription of Ashby's notebook from 1948-1949       
(36/277) 2461
But does this really give enough generality? Shouldn't some of the S's act between M and M? Are we going to get funny properties that I have not expected? So the step-functions control the system effectively? The behaviour of an M, M1 say is defined by dM1/dt=f1(M1,M,...M; S1, S2...) How it reacts to other M's as determined by this equation and from this equation- form there is no doubt that each can alter the functional form. So there's in fact any real limitation in S-> M1-> M2 for the effect of M1 on M2 as compared with, say M1-> S-> M2 (ignoring that S allows only constant values). I don't see it clearly but the form of the equation above suggests strongly that there is no necessary limitation. So long as some effect does get from variable to variable we can put no bounds to its effectiveness. Summary: Multistable system point....

<sup>5</sup> From transcription of Ashby's notebook from 1948-1949       
Note that it all depends on the peculiar behaviour of the variable [figure], which is called a step-function. But this deserves a separate paragraph     
    
Summary. A break may be treated as a mere incident in the development (in time) of one machine. Also one machine may be considered as split into two parts with a break between if one of the variables is a step-function of the time (see next paragraph). A break is a change of organization. Changes of organization have two causes: 1) Due to conditions outside the machine, which are arbitrary parameter changes, + are my doing. 2) due to conditions inside the machine- a break if we ignore the cause (30 of 271) 995......   

<sup>6</sup> From transcription of Ashby's notebook from 1948-1949       
(221/277) 2645      
making the machine perhaps more irresistable if it encounters opposition. (6) If x=a(q-x)+ky} y=l(x-q)-ay} then it has a resting state at x=q, y=0. Its determinant is |-a k| |l -a|, and its characteristic equation [Equation].Its latent roots are -a+_[Square root]kl. So whatever k and l are, they can only cause oscillation or lessen the stability. This sort of feedback is obviously not necessary for stability and goal-seeking. There seems therefore to be no doubt that Summary: Goal-seeking behaviour does not necessarily imply feedback. (c't'd p.2650 and 2654). (222/277) 2646......       

<sup>7</sup> From transcription of Ashby's notebook from 1941-1942         
Summary. An example of neutral cycle in a differential is given. (26 of 271) 991. 13 Aug 41......     

I have be reinvestigating the conditions etc of breaks (p. 893). In particular the question of whether a break-surface specifies everything (p.898)......     

Giving the results briefly we have, firstly, a break is a change of organisation. Next, because the break events are actually natural, however much of a nuisance, they must therefore be deductible from the immediately preceding [sic] state of the system and that therefore it is always possible to set up a new substitution which shall comprehend the previous substitutions, [equations] applying before the break and [figure] applying after the break........     

<sup>8</sup> From transcription of Ashby's notebook from 1947-1948             
20 Dec '47 2304 On p.2181 I noted that homoeostasis means constancy, & constancy means independence. But independence what of what? The answer is now obvious. Man, & every animal, is dominated by the gene- pattern. Even if his intelligence is not due to synapses prescribed in detail by genes it is more the less produced by step-functions put in en bloc by the genes. And why do they want the animal to be intelligent? Obviously to protect the gene-pattern.
(67/184) 2315     

And why homoeostasis? If we say that hemoeo--stasis is necessary for, say, the brain to work properly, we are explaining in a circle. We must look for something outside the homoeostatic set as explanation and cause. To the gene pattern, homoeostasis successfully achieved is a guarantee that the genes can get safely to their next pattern. Genes which form homoeostatic mechanisms around themselves survive, since they are insulated from the vagaries of the world. Those who neglect this precaution perish. We are, therefore, walking incubators for the protection of our testicles. Is this true or is it not? Summary: Homoeostasis is ultimately produced by the gene-pattern, and it protects the gene-pattern from the dangers of the world because the constancy means independence.     

<sup>9</sup> From transcription of Ashby's notebook from 1947-1948         
(45/184) 2293 remain." 27 Nov '47 London,I.D, Psych. Rev, 1944, 51, 266-291. He examines Kurt Lewin's "topological psychology" & leaves it exposed as a presumptions mass of verbiage. Incidentally he says: "Physical laws are nothing more than symbolic "descriptions of observed regular successions of "states in limited fields of phenomena.".....      

5 Dec '47 In society, when conditions get too bad, e.g. a crime wave develops, the passing of a law represents (a) a step-function change, (b) due to a variable exceeding a critical surface......      

<sup>10</sup> From transcription of Ashby's notebook from 1941-1942         
13 Aug 41. In the previous section, and p. 965, we noted the profound importance of variables which stay at one value for a time and then suddenly change to a new, constant value: [figure]. Owing to its shape I propose to call such a function a "step-function." We new define it. We may easily define it straight away for several variables.....

(31 of 271) 996.....     
* I have decided to drop the necessity for strictly two values, allowing the value on the I-surface to be anything. A step-function [figure] is a function of n variables [figure] , such that [figure] has only two numerical values* [arrow pointing above] possible/ except perhaps on the I-surface,/ and is/a/ single-valued function of its arguments. SO far this simply gives an arbitrary scattering of two number [figure] and [figure] throughout the x-space without any continuity. But this is of little use. We want the [figure]'s to be collected together, also the [figure]'s. This means there must be a boundary where they meet. So we add the further restriction that this surface must exist and be specifiable as a surface [figure] value [figure], and on the other side of it [figure]. If there are complications we may restrict ourselves to some suitably marked out region of the x-space if we don't want all of it.......

<sup>11</sup> From transcription of Ashby's notebook from 1948-1949      
(87/277) 2511..... variables, x<- ->y, we can have (a) positive feedback with stability, e.g. |-2 +1| r1=-4 |+1 -2| r2=+3 stable (p.1862) (b) negative feedback with instability, e.g. |+2 +1| r1=+4 |-1 +2| unstable (p.1862) This goes on even when systems are larger. Thus [Figure] has five feedbacks involved: [Figures] These may be some negative & some positive, thus |. -1 +1| |-1 . +1| has them, in order, |-1 +1 .| pos, neg, pos, pos, neg. Again we can completely tear up the "feedback" criterion. Thus: (c)All feedbacks positive, yet stable: |-3 1 -1| r1=-9 |1 -3 -1| r2=+24 |-1 -1 -3| r3=-16 |-9 1|=-200 |-16 24| (Its roots are -4, -4, -1, checked) Stable......

<sup>12</sup> From transcription of Ashby's notebook from 1948-1949    
If now this system is fitted up with feedback(all like MacColl). (100/277) 2524......    
[Diagram] then n=1/p-a(o+mn) or [Equation]      
p.18 we find the root of the equation in p 1-m*1/p-a=0 i.e. p=a+m For stability p must be negative (it is clearly real). m<-a. E.g. if a=-2 then m<+2. As all we need is that a+m is to be negative, we can have (a) m positive & the system still stable (if a is even more negative) (b) m negative and the system unstable (if a is even more positive.) Summary: This concept of negative feedback is most unsuitable as a fundamental concept......    

<sup>13</sup> From transcription of Ashby's notebook from 1948-1949    
16 Aug '48 Re the real existence of neurofibrils, J. G Greenfield in a review of the facts..... (115/277) 2539.....
(J. Neurol. Psychiat. 1936,1,306) cites several authors and accepts their real existence. They have seen in tissue cultures of chick embryos, in the living antennae of young crustaceans, and in the large nerve of the lobster's claw. Summary: Neurofibrils exist. 16 Aug' 48 One of the experiments I have tried with the homeostat is to force it to adopt some reaction feature by the simple process of driving it over a critical state when, & only when, it does not show it. Obviously the terminal state will show the feature. It should be noted that this "driving beyond a critical state", like a punishment, could be done equally well by a small automatic gadget attached. When I do it, I am that gadget. So the concept of "teaching" or "training" necessarily involves that the trainer becomes........

<sup>14</sup> From transcription of Ashby's notebook from 1948-1949   
(116/277) 2540.....  a part of the whole system, engages in two-way relation with the rest of the system. The two ways behaviour, i.e. whether he will or will not punish, and what he does controls the system, i.e. whether it will or will not undergo a change of set. Such systems, therefore, with the experimenter included, will have the usual property of being ultra--stable. Furthermore they are identical with systems where one ultrastable part is joined to some other part which insists that the terminal set must conform to some requirement. The well--known properties of a system being "trained" may therefore be carried over to any system of the type [Diagram of ultrastable system].......     

<sup>15</sup> From transcription of Ashby's notebook from 1931-1939
(169/290) 572. is not so much a theory as a new way of stating what is known......      
29 May 39     
Studies in the diffusion of, say, acetyl choline in the C.N.S. We reuire first to find the diffusion subsequent to the sudden liberation of a little mass of substance at a given point. Suppose all is at concentration 0, except in a sphere of radius R at the origin of concentration C. Then, to keep a $constant amount of substance, we let R->O & C->∞ such that 4/3π(R^3)C=S, say. S is te amount of substance......      

<sup>16</sup> From transcription of Ashby's notebook from 1939-1941      
26 June 41
Theorem: parameters control variables only by altering neutral points (and their surrounding fields). Consider a point in a field: (figure) itself is quite independant of this. So if a parameter does ultimately affect a variable it must be: parameter -> field -> variable. The part: field -> variable holds true only if the variable is moving. So for a parameter to affect a variable, it can affect it only by affecting its course and development. But this is entirely determined by the neutral points and their surrounding fields. So parameters can affect variables only by altering neutral points (and adjacent fields). (See p. 979)........      

<sup>17</sup> From transcription of Ashby's notebook from 1941-1942      
(138 of 271) 1103....... and it is therefore inadmissible to hypothesize too many break-surfaces depending on one variable. Suppose v has not room physically for more than 5 break variables h directly dependant on v. What ways are possible to get more protection for v? Find all ways + prove it. (Don't just copy the nervous system: I want an independant theorem).
First of all, as we are really discussing my break-theory, the only way I am interested in is to get more h's + thus more I's. But as v cannot control them directly, they must depend on new variables u which must be properly joined on to v. v must deputise. Each new u may properly be allowed a ration of 5 new h's, + thus 5 I's.......      

<sup>18</sup> From transcription of Ashby's notebook from 1945-1947     
Have I mentioned before my illustration of dynamic (205 of 304) (page 2159) equilibrium as shown by a person driving a car?     
Suppose there is a small movement of the wheel to one side. Immediately the streams of light coming back to the retina start changing their pattern; this causes further changes in the brain + ultimately changes come down the arms as "feedback" to the initial disturbance. But it is always found in the trained driver that the feedback is matched to the initial disturbance so that the motion is destroyed. While in the untrained the feedback may be such as to cause oscillations of increasing amplitude or a simple divergence to occur.      

<sup>19</sup> From transcription of Ashby's notebook from 1945-1947     
At any rate, the road has definite limits; the subsequent motion of a trained diver is convergent, that if the untrained driver divergent. Summary: Example of coordination + training as equilibrium in a dynamic system. An experimental follow up of Nyquist is Peterson, E, Kreerm, JG + Ware LA, Bell System Tech J, 1934, Vol 13, p 680. They mention Routh's "Advanced Rigid Dynamics" as constraining much on stability....... (206 of 304) (page 2160)        

<sup>20</sup> From transcription of Ashby's notebook from 1947-1948        
24 Dec '47 Recent papers seem to be using the ides of feedback freely, e.g. McCulloch, Darrow, Wiener. The idea should be related to mine. (See also pp. 2262 2265 2272) The main authority is MacColl. p.10 makes it obvious that the simple feedback is just another name of the system [Figure] But my reacting "circuits" are much more complex, though on p.72 he shows one equivalent to [Figure] (Tracing round shows it to be fully joined). So a "feedback" in included in my schemes as a very simple case. My chief difficulty is the unclear relation between the "p" method of MacColl & my differential equation method. I must go into it some time. Summary: Feedback....... (69/184) 2317        
