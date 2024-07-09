<div align= "center">
    <img src="https://capsule-render.vercel.app/api?type=slice&color=0:d4e3fe,100:000000&height=120&text=AICC&animation=fadeIn&fontColor=bcc2d2&fontSize=90" />
</div><br>
- AI Closed Caption <br>
* whisper 예외처리 개선 => 문자 <-> 숫자 변환 / 띄어쓰기 예외처리 필요
<br>
<li> 기존 whisper wer : 8.66% / hand_operated 조정 후 wer : 5.62%
</li>
<li> 기존 tiktoken wer : 13.61% / hand_operated 조정 후 wer : 6.87%</li><br>
- Evaluation tool model<br>
<li> tiktoken code parameter 조정 필요 (띄어쓰기, 숫자 <-> 문자)</li>
<li> 약어 u.s -> us 에 대한 출력 오류 개선 필요</li><br>
- LLM model 기반 Data-refine tool 개발<br>
<li> OpenAI LLM model : LLAMA </li>
<li> OpenAI GPT 기반 Data-refine 프롬프트 개발



