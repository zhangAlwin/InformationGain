# InformationGain
中文：计算信息增益 English  : calculating the Information Gain 

----Information gain example

there are two kinds of apples, and we know the [color,height,weight] of the apple
like :

[1,0,0] class label:good 

[1,0,1] class label:bad

and we can calculate the information gain of different features

color :0 ; height: 0; weight: 1 bit.

----Example
    X = np.array([[0,1,1,0,1,1,0],[0,1,0,0,1,0,0],[0,1,0,0,1,1,0]])
    y = [2,3,3]
    ig = InformationGain(X, y) # calculate
    # get the result 
    ig.get_result()
