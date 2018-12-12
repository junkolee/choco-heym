# choco-heym
클라우드 컴퓨팅 프로젝트

Amazon Rekognition 에 대해서 공부하고 실행해보는 프로젝트.

먼저 aws cli를 활용하여 이미지 파일을 통해 실습을 해보았으며 

추가로 aws cli로 비디오 파일에 startlabelsdetection api를 활용해 실습을 해보았고 

최종적으로 aws sdk 를 활용해 자바 코드를 통한 실습으로 제대로 된 결과가 나오는 것을 확인하였으며 

사용한 api는

StartLabelsDetection

StartFaceDetection

StartPersonTracking

StartCelebrityRecognition

StartContentModeration

GetLabelsDetection

GetFaceDetection

GetPersonTracking

GetCelebrityRecognition

GetContentModeration

들을 활용하였다.

자격 증명과 sns, sqs 에서 가장 많은 문제가 발생했으며 공부하여 해결하였다.

aws 개발자 안내서, 네이버 블로그, 여러 구글 링크들과 유튜브 rekognition 관련 영상을 참조하였다.
