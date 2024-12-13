# GDG Tokyo Hands-On 20241213 Genkit

https://tanabee.github.io/genkit-codelab/ja/

## 注意

- windows gitbash ではcurlのパラメータは`"`で囲む必要がある。
  + curl -H "Content-Type: application/json" -d "{\"contents\":[{\"parts\":[{\"text\":\"Explain Firebase in under 100 words.\"}]}]}" -X POST "https://generativelanguage.googleapis.com/v1beta/models/gemini-1.5-flash-latest:generateContent?key=YOUR_API_KEY"
- 