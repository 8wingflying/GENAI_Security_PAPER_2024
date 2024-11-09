# GENAI_Security_2024
- [LLM4Decompile: Decompiling Binary Code with Large Language Models](https://arxiv.org/abs/2403.05286)
- [LLM-Based Misconfiguration Detection for AWS Serverless Computing](https://arxiv.org/abs/2411.00642)
- [AttackQA: Development and Adoption of a Dataset for Assisting Cybersecurity Operations using Fine-tuned and Open-Source LLMs|2411.0107](https://arxiv.org/abs/2411.01073)
- [RAG4ITOps: A Supervised Fine-Tunable and Comprehensive RAG Framework for IT Operations and Maintenance|2410.15805](https://arxiv.org/abs/2410.15805)
- ["Ghost of the past": identifying and resolving privacy leakage from LLM's memory through proactive user interaction](https://arxiv.org/abs/2410.14931)
# LLM Security
- [Data Extraction Attacks in Retrieval-Augmented Generation via Backdoors|2411.01705](https://arxiv.org/abs/2411.01705)
- [HijackRAG: Hijacking Attacks against Retrieval-Augmented Large Language Models|2410.22832](https://arxiv.org/abs/2410.22832)
- [Real-time Fake News from Adversarial Feedback](https://arxiv.org/abs/2410.14651)
- [Backdoored Retrievers for Prompt Injection Attacks on Retrieval Augmented Generation of Large Language Models](https://arxiv.org/abs/2410.14479)
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
# LLM 大型語言模型
- [66個大型語言模型LLM經典論文(2023)](https://tomohiroliu22.medium.com/66%E5%80%8B%E5%A4%A7%E5%9E%8B%E8%AA%9E%E8%A8%80%E6%A8%A1%E5%9E%8Bllm%E7%B6%93%E5%85%B8%E8%AB%96%E6%96%87-0fcdab74e822)
- [LLaMA: Open and Efficient Foundation Language Models | 2302.13971](https://arxiv.org/pdf/2302.13971)
- [Bielik 7B v0.1: A Polish Language Model -- Development, Insights, and Evaluation|2410.18565](https://arxiv.org/abs/2410.18565)

# RAG_REVIEW
- [A Comprehensive Survey of Retrieval-Augmented Generation (RAG): Evolution, Current Landscape and Future Directions](https://arxiv.org/abs/2410.12837)

# RAG
- [RuleRAG: Rule-guided retrieval-augmented generation with language models for question answering|2410.22353](https://arxiv.org/abs/2410.22353)
- [AutoRAG: Automated Framework for optimization of Retrieval Augmented Generation Pipeline|2410.20878](https://arxiv.org/abs/2410.20878)
- [Developing Retrieval Augmented Generation (RAG) based LLM Systems from PDFs: An Experience Report|2410.15944](https://arxiv.org/abs/2410.15944)
# LLM_Technique
- [A Comparative Study of PDF Parsing Tools Across Diverse Document Categories](https://arxiv.org/abs/2410.09871)
# LLM Application
- [OpenCoder: The Open Cookbook for Top-Tier Code Large Language Models](https://arxiv.org/abs/2411.04905)
- [Code Llama: Open Foundation Models for Code]()
- [Exploring Demonstration Retrievers in RAG for Coding Tasks: Yeas and Nays!](https://arxiv.org/abs/2410.09662)
- [Using GPT Models for Qualitative and Quantitative News Analytics in the 2024 US Presidental Election Process|2410.15884](https://arxiv.org/abs/2410.15884)
- [Leveraging Retrieval-Augmented Generation for Culturally Inclusive Hakka Chatbots: Design Insights and User Perceptions|2410.15572](https://arxiv.org/abs/2410.15572)
- [Agents4PLC: Automating Closed-loop PLC Code Generation and Verification in Industrial Control Systems using LLM-based Agents](https://arxiv.org/abs/2410.14209)
- [Checker Bug Detection and Repair in Deep Learning Libraries](https://arxiv.org/abs/2410.06440)

# Small Language Model
- [A Comprehensive Survey of Small Language Models in the Era of Large Language Models: Techniques, Enhancements, Applications, Collaboration with LLMs, and Trustworthiness |2411.03350](https://arxiv.org/abs/2411.03350)
