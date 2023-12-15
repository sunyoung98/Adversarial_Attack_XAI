# dog_cat_classifier

pretrained_models : https://drive.google.com/file/d/1Ue6e_9bkexjz6MqlVowfT8FnfRHcmtfy/view?usp=drive_link

이 프로젝트는 성균관대학교의 데이터기반 보안과 프라이버시 수업의 팀프로젝트 일환으로 진행되었음.

[분류 모델 구축 및 성능 비교]
1-1. classification : dogs and cats 데이터셋을 기준으로 여러 모델의 전이학습을 수행하는 코드를 작성함.
1-2. model-test : 해당 분류 모델들의 성능을 비교함.

[lime 시각화 생성 및 ifgsm 추가]
2-1. lime-ifgsm : ifgsm 공격을 가한 뒤와 원본의 lime 결과물 비교.
2-2. ifgsm-attack-xai : 여러 영역에 공격을 가한 뒤의 이미지 결과물 생성

[lime 시각화 생성 및 deepfool 추가]
3-1. vgg-deepfool : deepfool 공격을 가한 뒤 원본 lime 결과물 비교.
3-2. deepfool-lime-make-dataset : 여러 영역에 공격을 가한 뒤의 이미지 결과물 생성

[해당 공격들에 대한 결과 reporting 및 finetuning]
4-1. check_accuracy_and_fine_tuning_IFGSM : IFGSM 공격의 경우
4-2. vgg-vit-deepfool-finetune : deepfool 공격의 경우

cat_dog_df.csv : 데이터셋 분할된 것을 고정해놓기 위함.
IFGSM_Sample : 공격을 가했을 때의 이미지들의 예시 사진들을 보여주기 위함.
