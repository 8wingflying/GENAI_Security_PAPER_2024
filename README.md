# GENAI_Security_2024
- [LLM4Decompile: Decompiling Binary Code with Large Language Models](https://arxiv.org/abs/2403.05286)
# LLM Security
- [Emoji Attack: A Method for Misleading Judge LLMs in Safety Risk Detection|2411.01077](https://arxiv.org/abs/2411.01077)
  - 越獄攻擊(Jailbreaking attacks)展示如何利用惡意提示誘騙大型語言模式 (LLM) 產生有害輸出。
  - 為了防止這些攻擊，通常會聘請其他 LLMs作為judges來評估生成內容的危害性。
  - 然而，依賴 LLMs作為評判可能會為檢測過程帶來偏差，進而損害評估的有效性。
  - 在本文中，我們表明，法官法學碩士與其他 LLMs一樣，也受到令牌分割偏差的影響。
  - 當令牌被分割成更小的子令牌並改變它們的嵌入時，就會出現這種偏差。
  - 這使得模型更難檢測有害內容。
  - 具體來說，這種偏差可能會導致子令牌與嵌入空間中的原始令牌顯著不同，從而導致對有害內容做出錯誤的「安全」預測。
  - 為了利用法官法學碩士中的這種偏見，我們引入了表情符號攻擊——一種將表情符號放置在令牌中以增加子令牌與其原始令牌之間的嵌入差異的方法。
  - 這些表情符號創建了新的標記，進一步扭曲了標記嵌入，加劇了偏見。
  - 為了應對表情符號攻擊，我們設計了提示來幫助法學碩士過濾掉不尋常的字元。
  - 然而，仍然可以透過混合使用表情符號和其他字元來繞過這種防禦。
  - 表情符號攻擊還可以與使用少量學習的現有越獄提示相結合，這使得法學碩士能夠使用表情符號產生有害的回應。
  - 這些回應經常被法學碩士法官錯誤地標記為“安全”，從而使攻擊得以溜走。
  - 我們對六位最先進的 Judge LLM 進行的實驗表明，
  - Emoji 攻擊允許 25% 的有害響應繞過 Llama Guard 和 Llama Guard 2 的檢測，
  - 而 ShieldLM 的檢測則高達 75%。
  - 這些結果凸顯了需要更強大的法官法學碩士來解決這個漏洞。
  - 我們的程式碼可在https://github.com/zhipeng-wei/EmojiAttack取得。 
# LLM
- [LLaMA: Open and Efficient Foundation Language Models | 2302.13971](https://arxiv.org/pdf/2302.13971)

# LLM Application
- [OpenCoder: The Open Cookbook for Top-Tier Code Large Language Models](https://arxiv.org/abs/2411.04905)
# Small Language Model
- [A Comprehensive Survey of Small Language Models in the Era of Large Language Models: Techniques, Enhancements, Applications, Collaboration with LLMs, and Trustworthiness |2411.03350](https://arxiv.org/abs/2411.03350)
