# eli5 (Codex)

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Platform](https://img.shields.io/badge/platform-Codex%20CLI-000000.svg)
![Format](https://img.shields.io/badge/format-SKILL.md-orange.svg)
![Ported from](https://img.shields.io/badge/ported%20from-Claude%20Code-6b57ff.svg)

어떤 주제든 5살짜리도 이해할 수 있게 설명해주는 스킬입니다.
[claude-community 마켓플레이스의 `eli5` 스킬](https://github.com/anthropics/claude-plugins-community/tree/main/eli5)을 Codex CLI(`~/.codex/skills`)에서 그대로 사용할 수 있도록 이식한 버전입니다.

## 사용법

```
/eli5 how does DNS work
```

큰 그림과 최소한의 텍스트로 구성된 HTML artifact를 생성해, 해당 주제를 전혀 모르는 사람도 바로 이해할 수 있도록 설명합니다.

## 설치

```sh
git clone <this-repo-url> ~/.codex/skills/eli5
```

또는 이미 클론해 둔 저장소를 심볼릭 링크로 연결합니다.

```sh
ln -s /path/to/eli5-codex ~/.codex/skills/eli5
```

## 출처

원본 스킬: [`eli5` (claude-community marketplace)](https://github.com/anthropics/claude-plugins-community/tree/main/eli5), 작성자 Thariq Shihipar, MIT License.
이 저장소는 동일한 `SKILL.md` 형식을 Codex CLI 스킬 디렉터리 구조에 맞춰 옮긴 것입니다.

## 라이선스

MIT License. [LICENSE](./LICENSE) 참고.
