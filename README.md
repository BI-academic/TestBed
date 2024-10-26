# TestBed
Testbed for organization

기본적인 깃 사용법을 익히거나, 테스트 할 수 있는 공간입니다. 

아무것도 모르는 상태로 리포 사용하는것 보다는 이곳에서 에러도 익히고, 실수도 익히면서 익숙해 지고 난 뒤에 프로젝트를 진행하시는게 좋을것 같아 만들었습니다. 

## Overview of branching strategy
- 깃 브랜칭 전략은 개발 시 아주 중요한 요소입니다. 이미 많은 주요 회사들은 여러가지 브랜칭 전략을 가지고 있으며 각 팀에서도 이를 각각 조정하여 자신들의 agile development에 맞게끔 사용하고 있습니다. 다음 링크를 참고하시고 개발해 주시면 되겠습니다. Git workflow가 가장 범용적이고 유명한 전략이니 참고 바랍니다.

- [ Git Workflow ](https://www.atlassian.com/git/tutorials/comparing-workflows)
- [ Trunk based workflow ](https://www.atlassian.com/continuous-delivery/continuous-integration/trunk-based-development)

## Example of git workflow in this repository
- 현재 Repository는 main, dev, test branches를 가지고 있으며, 개발자가 하나의 feature branch를 dev로 부터 생성 후에 Merge request를 dev로만 해야합니다. Feature branch는 개발하고자 하는 이름이나 내용을 적는것이 일반적이고 각각의 feature에 대응하는 issue ticket을 연결하는 것이 좋습니다.

## Ruleset
- 각각의 repository는 Ruleset을 가지고 있는 것이 좋습니다. main과 test 브랜치는 보호 해야하며 다음을 참고해서 ruleset을 생성하세요 (link)[https://github.com/BI-academic/TestBed/settings/rules/2400897]
