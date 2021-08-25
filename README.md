# 3DBall Sample
인천정보과학고등학교 게임 머신러닝 실습용입니다. 

## 가상환경 활성화 방법
```
pip install ml-agents==0.16.1
```

### 가상환경 생성
```
conda create -n <가상환경명>
conda create -n my3dball
```

### 가상환경 활성화
```
conda activate <name>
```

### 가상환경 리스트 확인
```
conda env list
```

### ML-Agents 학습하기
```
mlagents-learn "<yaml경로>" --run-id <folder_name>
```

### cudart64_110.dll 에러 대처
```
https://developer.nvidia.com/cuda-11.0-download-archive?target_os=Windows&target_arch=x86_64&target_version=10&target_type=exenetwork
```
다운 받아 설치(하단의 옵션 2개는 제외하고 설치)

### 가상환경 삭제 
```
conda remove --name <name> --all
```
