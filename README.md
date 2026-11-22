# Study Notes

YOLO·VLM(Vision-Language Model)의 개념 및 아키텍처 비교와, 고전 역학부터 다관절 로봇 공학까지의 Kinematics·Dynamics 핵심 이론을 정리한 기술 노트입니다.

## 목차

1. **[VLM과 YOLO 개념, 네트워크 구조 및 차이점](./1.VLM_YOLO.md)**
   - YOLO (Backbone–Neck–Head, 그리드·손실 함수·NMS, v1~v11 발전사)
   - VLM (Encoders–Fusion/Projector–Decoder, 주요 태스크)
   - 입출력·태스크, 네트워크 구조(Backbone–Neck–Head vs Encoders–Fusion/Projector–Decoder) 및 핵심 연산(CNN vs Transformer) 비교

2. **[VLM 주요 종류, 아키텍처별 차이점 및 모델별 장단점](./2.VLM_Models.md)**
   - 4가지 주요 계열: 듀얼 인코더(CLIP, SigLIP), 정렬·통합형(ALBEF, BLIP), 토큰 압축 브릿지(BLIP-2, Flamingo), 직접 투영 생성형(LLaVA, Qwen2-VL, InternVL 2/2.5)
   - 계열별 핵심 차이 비교표 및 모델별 장단점 정리

3. **[Kinematics와 Dynamics](./3.Kinematics_Dynamics.md)**
   - 고전 기구학·운동역학 (질점 좌표계 $`x\text{-}y`$ / $`n\text{-}t`$ / $`r\text{-}\theta`$, 강체 평면 운동, 힘·에너지·운동량 해석, 관성 텐서)
   - 로봇 기구학 (C-space·자유도, $`SO(3)`$ / $`SE(3)`$·스크류 이론, 지수곱 정기구학, 자코비안·특이점, 수치적 역기구학)
   - 다관절 로봇 동역학 (표준 방정식 $`\tau = M(\theta)\ddot{\theta} + c(\theta,\dot{\theta}) + g(\theta)`$, 라그랑지안, 재귀 뉴턴–오일러 RNEA, 반사 관성)
