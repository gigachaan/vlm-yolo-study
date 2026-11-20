# VLM & YOLO Technical Notes

YOLO와 VLM(Vision-Language Model)의 개념, 네트워크 구조 비교 및 주요 VLM 모델별 아키텍처와 장단점을 정리한 문서입니다.

## 목차

1. **[VLM과 YOLO 개념, 네트워크 구조 및 차이점](./1.VLM_YOLO.md)**
   - YOLO (Backbone–Neck–Head, 그리드·손실 함수·NMS, v1~v11 발전사)
   - VLM (Encoders–Fusion/Projector–Decoder, 주요 태스크)
   - 입출력·태스크 및 기반 네트워크(CNN vs Transformer) 비교

2. **[VLM 주요 종류, 아키텍처별 차이점 및 모델별 장단점](./2.VLM_Models.md)**
   - 4가지 주요 계열: 듀얼 인코더(CLIP, SigLIP), 정렬·통합형(ALBEF, BLIP), 토큰 압축 브릿지(BLIP-2, Flamingo), 직접 투영 생성형(LLaVA, Qwen2-VL, InternVL 2/2.5)
   - 계열별 핵심 차이 비교표 및 모델별 장단점 정리
