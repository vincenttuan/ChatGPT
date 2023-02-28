# ChatGPT
ChatGPT
<pre>

API 申請 (OpenAI GPT-3 Developer API)![image](https://user-images.githubusercontent.com/13216208/221784173-6096bf10-8676-4aab-bec8-73fb7cc090d1.png)
https://platform.openai.com/account/api-keys

每月 $18.00 美金免費額度![image](https://user-images.githubusercontent.com/13216208/221784280-86d8b745-7280-4241-af0a-e88db53b7c12.png)
https://platform.openai.com/account/usage

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

</pre>
