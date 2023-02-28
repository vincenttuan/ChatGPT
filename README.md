# ChatGPT
<img src="https://github.com/vincenttuan/ChatGPT/blob/main/page.png" width="300">
<p>
PDF Download : 
<a href="https://github.com/vincenttuan/ChatGPT/blob/main/ChatGPT.pdf">https://github.com/vincenttuan/ChatGPT/blob/main/ChatGPT.pdf</a>
<pre>

API 申請 (OpenAI GPT-3 Developer API)
https://platform.openai.com/account/api-keys

每月 $18.00 美金免費額度
https://platform.openai.com/account/usage

Request input:
curl https://api.openai.com/v1/completions \
  -H 'Content-Type: application/json' \
  -H 'Authorization: Bearer YOUR_TOKEN' \
  -d '{
  "model": "text-davinci-003",
  "prompt": "請問台灣與中國會開戰嗎",
  "max_tokens": 100,
  "temperature": 0,
  "n": 1
}'

Response output:
{
  "id": "cmpl-6oPeqFcHrVKSJRLlFz3Z5tVlYP",
  "object": "text_completion",
  "created": 1677473048,
  "model": "text-davinci-003",
  "choices": [
     {
       "text": "台灣與中國不會開戰，台灣與中國之間的關係是一種維持現狀的關係，台灣與中國之間的關係是一種和平共處的關",
       "index": 0,
       "logprobs": null,
       "finish_reason": "length"
     }
   ],
   "usage": {
	 "prompt_tokens": 25,
	 "completion_tokens": 100,
	 "total_tokens": 125
   }
}

</pre>
