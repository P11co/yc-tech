# 1주차 노트

Created: September 9, 2023 3:02 PM

OT: YC Tech 주제를 왜 백엔드로 정한이유: 백엔드의 수요가 가장 많다.

- Backend 직무
    
    [**www.roadmap.sh](http://www.roadmap.sh) → 생각보다 분야가 넓다… 많이 경험해 보는게 좋다**
    
    소프트웨어 개발 프로세스:
    
    1. 요구사항 분석
    2. API개발
    3. 테스트QA
    4. 배포
- REST API
    
    **Representational State Transfer: Roy Fielding’s Architecture for the web (2000)**
    
    - REST의 Components:
        - Resource (URI)
        - Verb (HTTP METHODS → GET)
        - Representations
    - REST의 특징:
        
        캐시 가능성 → 속도, 비용
        
        계층형 구조 → 암호화 계층 추가, 
        
    - [REST API Best Practices](https://www.freecodecamp.org/news/rest-api-best-practices-rest-endpoint-design-examples/):
        1. Use **JSON**
        2. Use **Nouns** (instead of verbs)
            
            > [mysite.com/getPosts](http://mysite.com/getPosts) → mysite.com/posts
            > 
        3. Name Collections with **Plural Nouns**
            
            > [mysite.com/](http://mysite.com/getPosts)post → mysite.com/posts
            > 
        4. Use **Status Codes** in Error Handling
            
            Makes things easier to debug
            
        5. Use **Nesting** on Endpoints to Show Relationships
            
            Tip: Avoid more than 3 layers
            
        6. Use **Filtering, Sorting, Pagination**
            
            https://mysite.com/posts?tags=javascript
            
        7. Use **SSL** (secure socket layer) for Security
        8. Be clear with V**ersioning**
        9. Provide accurate **API Documentation**
    - Spring Framework
        
        Inversion of Control
        
        Dependency Injection
        
        AOP 지원
        
    - 
    
    [1.pdf](1%E1%84%8C%E1%85%AE%E1%84%8E%E1%85%A1%20%E1%84%82%E1%85%A9%E1%84%90%E1%85%B3%2088b910e7323a4c81b7358f75c954bb22/1.pdf)
