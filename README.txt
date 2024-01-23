사전학습 모델 출처 : 논문 DaViT: Dual Attention Vision Transformer (ECCV 2022) 공식 Github
깃허브 주소 : https://github.com/dingmyu/davit/tree/main?tab=readme-ov-file

실제 사용 모델 : 위의 Github의 README.md 파일의 benchmarking 항목 중 Image Classification on ImageNet-1k 부분, DaViT-B 사용
사전학습 모델 다운로드 주소 (논문 공식 Github 주소에서 넘어올 수 있습니다.) : https://connecthkuhk-my.sharepoint.com/personal/u3007305_connect_hku_hk/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fu3007305%5Fconnect%5Fhku%5Fhk%2FDocuments%2FCodes%2F22%5FCVPR%5FDaViT%2Fbase%2Fmodel%5Fbest%2Epth%2Etar&parent=%2Fpersonal%2Fu3007305%5Fconnect%5Fhku%5Fhk%2FDocuments%2FCodes%2F22%5FCVPR%5FDaViT%2Fbase&ga=1

해당 링크를 통해 받은 파일 명( 제가 파일 이름을 변경했습니다. 기존 파일 이름 : model_best.pth.tar) : model_best_big.pth.tar
동일한 디렉토리에 해당 파일이 존재해야 코드가 정상적으로 작동합니다.

개발환경 : Ubuntu 20.04, Python 3.8, CUDA 11.4, Pytorch 1.10.0a0+3fd9dcf, Jupyter

사용 GPU : RTX3090

env.yaml : 수행 환경 관련 라이브러리 정보 (conda env export > env.yaml 명령어를 통해 얻은 파일)

timm 폴더 : pip을 통해 설치한 timm 라이브러리에서는 DaViT 모델 생성이 불가능해 첨부한 파일(timm 폴더, 동일한 디렉토리에 timm 폴더가 있어야 합니다.)를 통해 import해야 모델이 생성됩니다.
(위의 Github 주소의 timm 폴더와 동일합니다.)

2023_AICOSS_model_weight_EggTheProtein.pth : 최종 학습 모델 weight 파일, Private Score 복원 가능

AICOSS_2023_main_EggTheProtein_final : Private Score 복원 가능 파일, Jupyter 파일


