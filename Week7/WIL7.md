일단 시작하기 전에 고백 좀 하자면...  
이번 주차는 과제에 시간 투자를 평소보다 하지 못했다... 이리저리 이유를 말하는 건 핑계같으니까 하지 않겠지만,  
단순 시간이 없어서는 아닌 것 같기 때문에 조금 고민을 해봤다.. ~~분량 못채울거 같기도 하고...~~~  

- - -

일단 이론적인 배경이 너무 부실하다는 생각이 들었다.  
공식문서에 가서 읽어보려해도 영어라 막히는 건 둘째 치고, 납득이 잘 가지 않았다.  
```
Principal component analysis (PCA).

Linear dimensionality reduction using Singular Value Decomposition of the data to project it to a lower dimensional space. The input data is centered but not scaled for each feature before applying the SVD.

It uses the LAPACK implementation of the full SVD or a randomized truncated SVD by the method of Halko et al. 2009, depending on the shape of the input data and the number of components to extract.

It can also use the scipy.sparse.linalg ARPACK implementation of the truncated SVD.

Notice that this class does not support sparse input. See TruncatedSVD for an alternative with sparse data.

Read more in the User Guide.
```  
이것은 `sklearn.decomposition.PCA` 의 공식 설명이다.  
여기서 SVD나 LAPACK가 뭔지 알 수 없었고, `parameter`, `attributes`, `Methods` 에서도 완전히 이해를 했다고 말할 수 있는 것이 **거의 전무하다**고 생각한다.  
약간 코드를 치고 있지만 뜬구름을 잡는 느낌이 든다 해야하나...  
여기서 드는 생각은 일단 버티면서 경험해나가며, 내가 무엇이 부족한지를 깨닫고 앞으로 무엇을 해야하는지 고민해야겠다고 느꼈다.  
  
그리고 데이터를 처리하는 방법을 배우는 중인데, 정작 데이터에 대한 관심이 적었다는 것을 깨달았다.  
전에 했던대로 데이터를 일일이 해부하고, 시각화하고, 전처리하는 것까지는 아니더라도 적어도 어떤 특성들로 구성되어있는지, 뭐에 대한 것인지 정도는 알고 해야하지 않았나 생각이 든다...
  
그리고 영어공부도 좀 해야겠다는 생각이...  
  
여러모로 반성이 좀 많이 되는 주였던거 같다..  
약간 PCA 이론에서 벽 느끼고, 쓰는 거라 더 그럴지도...