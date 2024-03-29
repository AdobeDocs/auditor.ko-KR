---
description: 이 참조는 Adobe Experience Platform Auditor에서 태그 일관성을 확인하기 위해 수행하는 테스트에 대한 자세한 정보를 제공합니다.
seo-description: This reference provides more information about the tests Adobe Experience Platform Auditor performs for tag consistency.
seo-title: Tag consistency
title: 태그 일관성
uuid: 16271dd6-3587-4f33-92f8-54ec4a3d6469
exl-id: 681cf2f8-e022-4fb0-a06a-b4986710f501
source-git-commit: 286a857b2ff08345499edca2e0eb6b35ecf02332
workflow-type: tm+mt
source-wordcount: '105'
ht-degree: 100%

---

# 태그 일관성

이 참조는 Adobe Experience Platform Auditor에서 태그 일관성을 확인하기 위해 수행하는 테스트에 대한 자세한 정보를 제공합니다.

Platform Auditor의 일관성 테스트는 검사한 모든 페이지에서 일치하지 않는 것을 찾습니다. 이는 정확한 데이터 수집을 위해 사이트의 모든 페이지에서 동일해야 하는 값 또는 구성입니다.

<table id="table_4F9ED873BAF741D19BFB0F297B3A1FDB"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> 테스트 </th> 
   <th colname="col2" class="entry"> 기준 </th> 
   <th colname="col3" class="entry"> 권장 사항 </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> 
    <!--
      1.0.1 
    --> <p><b>Analytics - 일관된 코드 버전 </b> </p> <p>가중치: 5 </p> <p><a href="https://docs.adobe.com/content/help/ko-KR/analytics/implementation/home.html" format="html" scope="external"> 추가 정보</a> </p> </td> 
   <td colname="col2"> <p> 둘 이상의 Analytics 코드 버전을 찾았습니다. </p> </td> 
   <td colname="col3"> <p>Analytics의 모든 인스턴스를 현재 버전으로 바꿉니다. </p> </td> 
  </tr> 
 </tbody> 
</table>
