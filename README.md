# 유전자-질병 관계 해석 프로젝트

## 프로젝트 개요
유전자-질병 관계 해석 프로젝트는 유전자(Gene), 변이(Variant), 질병(Disease) 개체를 추출하여 유전자-질병 간 관계성을 예측하는 Transformer 기반의 관계 추출 시스템입니다.

## 워크플로우
- NER(Named Entity Recognition) : 유전자, 변이, 질병 개체 추출
- RE(Relation Extraction) : 유전자와 질병 간 관계 예측
- Knowledge Graph : 추출된 정보를 바탕 그래프 분석

## Reference
https://bradylamson.com/p/named-entity-recognition-a-transformers-tutorial/