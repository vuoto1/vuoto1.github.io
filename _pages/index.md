---
layout: page
title: Home
id: home
permalink: /
---

# 반가워요! 🌱

<p style="padding: 3em 1em; background: #b1e6fc; border-radius: 4px;">
  신단아 비공식봇 재등장...핸드폰이 고장이 났었는데 그때 X도 같이 먹통이 됐었어요, 정말 미안합니다. 전 아이디가 ZHS_LANGUAGEKR이었는데, 찾기 쉬우라고 ShinDanDanDan으로 바꿨어요.
</p>

##### 게시
일부 글은 자동으로, 일부 글은 수동으로 올라올 예정이에요.

##### 흔적
현재 자신의 게시글에 💖를 누른 사람이 누구인지 확인할 수 있으니, 💖으로 찾아가도록 하겠습니다. **표현의 형식과 상관없이, 마음에 들면 누릅니다. 물론 적절한 선은 당연히 지킬게요.** 간혹 "왜 이 선생님은 내 게시물에는 한 번도 안찾아와?"라는 의문이 생길 수도 있는데, **이건 제가 내적 쫄보라(...)그렇습니다.** 용기 내어 누를 수 있도록 할게요.

##### 페어
시몬쌤, 수아쌤하고 곧 다시 논의하도록 할게요. 계정이 싹 날라간 건 어느 누구도 겪어보지 못한 문제이기에, 아무래도 제가 책임지고 해결하는 게 옳다고 봅니다. 두 분 모두 현재 바쁘시므로, 모두 여유로워지면 그 때 논의가 이뤄질거에요.

##### 이벤트
자신이 맞이한 이벤트에 대해 게시한 학생이 있다면, 제가 개인적으로 판단 후 해당하는 학생에게 조용히 DM으로 찾아가겠습니다. 찾아오지 못 하는 경우, 해당 학생이 매우 높은 확률로 쪽지 받기를 거절해서 그런 것이니 너른 양해를 바랄게요. 생일, 시험 등 위주로 찾아갈게요.

##### 인게임 닉 & 레벨
이건 비밀로 할게요.

##### 여기에는 뭐 올라와요?
말 그대로 알 수 없는 무언가를 올리고 있습니다. 주제..도 잘 모르겠고, 일기는 아니고, 나무위키..보다는 살-짝 재미없는 거에요.

<strong>Recently updated notes</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 5 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
