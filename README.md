# springboot-scaffold
원어적 뜻
스캐폴드(scaffold)의 원어는 중세 라틴어의 'scadafaltum' 또는 올드 프랑스어의 'escafault'에서 유래되었으며, '임시 작업대' 또는 '건설 현장에서 사용되는 작업 플랫폼'을 의미합니다. 기본적으로 스캐폴드는 건축가와 건설 노동자가 높은 곳에서 작업할 수 있도록 지지하는 구조물이나 플랫폼을 지칭합니다. 이러한 구조물은 일시적으로 설치되며, 건물의 외부 또는 내부에서 작업의 접근성을 높이고 안전을 보장하는 데 사용됩니다.

소프트웨어 개발에서의 의미
소프트웨어 개발에서 "스캐폴드"는 약간 다른 의미로 사용됩니다. 여기서 스캐폴딩은 개발자가 새로운 프로젝트나 기능을 빠르게 시작할 수 있도록 미리 준비된 코드 또는 프레임워크 구조를 말합니다. 이는 기본적인 프로젝트 구조, 데이터 모델, API 연결 등을 미리 설정해 놓은 것으로, 개발자가 반복적인 작업을 줄이고 핵심 기능 개발에 더 집중할 수 있게 해줍니다.

필수 의존성 
스캐폴딩을 생성할 때 고려해야 할 몇 가지 기본 의존성이 있습니다. 이러한 의존성은 대부분의 Spring Boot 애플리케이션에 유용합니다.

- Spring Web: RESTful 애플리케이션을 구축하는 데 필요합니다.
- Spring Data JPA: 데이터베이스와의 상호 작용을 단순화합니다.
- H2 Database: 개발용 인메모리 데이터베이스로 사용할 수 있습니다.
- Spring Security: 애플리케이션 보안을 추가합니다.
- Lombok: 보일러플레이트 코드를 줄이는 데 도움이 됩니다.

# 프로젝트 구조 예시 
<img width="547" alt="image" src="https://github.com/jeonck/springboot-scaffold/assets/11763994/0facd567-c36e-48b4-9713-c0c5cc35b8e9">


# push 절차 
cd /path/to/your/spring-boot-project  

git init  
git branch -m main
git remote add origin https://github.com/yourusername/your-repository-name.git  
git pull origin main
git add .  
git commit -m "Initial commit"  
git push origin main  

