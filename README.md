# Awesome-Jailbreak-on-LLMs

Awesome-Jailbreak-on-LLMs is a collection of state-of-the-art, novel, exciting jailbreak methods on LLMs. It contains papers, codes, datasets, and evaluations. Any additional things regarding jailbreak are welcome. Any problems, please contact yueliu19990731@163.com. If you find this repository useful to your research or work, it is really appreciated to star this repository. :sparkles:






## Papers


### Jailbreak Attack



#### White-box Attack
| Year | Title                                                        |  Venue  |                            Paper                             |                             Code                             |
| ---- | ------------------------------------------------------------ | :-----: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| 2024.05 | **AutoDAN: Generating Stealthy Jailbreak Prompts on Aligned Large Language Models (AutoDAN)** |   ICLR    | [link](https://arxiv.org/pdf/2310.04451)  |                              [link](https://github.com/SheltonLiu-N/AutoDAN)                               |
| 2024.02 | **Attacking large language models with projected gradient descent (PGD)** |   arXiv    | [link](https://arxiv.org/pdf/2402.09154)  |                              -                               |
| 2023.12 | **AutoDAN: Interpretable Gradient-Based Adversarial Attacks on Large Language Models (AutoDAN)** |   NeurIPS Workshop    | [link](https://arxiv.org/abs/2310.15140)  |                              [link](https://github.com/llm-attacks/llm-attacks)                               |
| 2023.07 | **Universal and Transferable Adversarial Attacks on Aligned Language Models (GCG)** |   arXiv    | [link](https://arxiv.org/pdf/2307.15043)  |                              [link](https://autodan-jailbreak.github.io/)                               |






#### Black-box Attack

| Time | Title                                                        |  Venue  |                            Paper                             |                             Code                             |
| ---- | ------------------------------------------------------------ | :-----: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| 2024.06 | **When LLM Meets DRL: Advancing Jailbreaking Efficiency via DRL-guided Search (RLbreaker)** |   arXiv    | [link](https://arxiv.org/pdf/2406.08705) |                              -                               |
| 2024.06 | **Jailbreaking Leading Safety-Aligned LLMs with Simple Adaptive Attacks** |   arXiv    | [link](https://arxiv.org/pdf/2404.02151) |                              [link](https://github.com/tml-epfl/llm-adaptive-attacks)                               |
| 2024.06 | **A Wolf in Sheep’s Clothing: Generalized Nested Jailbreak Prompts can Fool Large Language Models Easily (ReNeLLM)** |   NAACL    | [link](https://arxiv.org/abs/2311.08268) |                              [link](https://github.com/NJUNLP/ReNeLLM)                               |
| 2024.06 | **QROA: A Black-Box Query-Response Optimization Attack on LLMs (QROA)** |   arXiv    | [link](https://arxiv.org/abs/2406.02044) |                              [link](https://github.com/qroa/qroa)                               |
| 2024.05 | **Multilingual Jailbreak Challenges in Large Language Models** |   ICLR    | [link](https://arxiv.org/pdf/2310.06474)  |                              [link](https://github.com/DAMO-NLP-SG/multilingual-safety-for-LLMs)                               |
| 2024.05 | **GPT-4 Jailbreaks Itself with Near-Perfect Success Using Self-Explanation (IRIS)** |   ACL    | [link](https://arxiv.org/abs/2405.13077) |                              -                               |
| 2024.05 | **"Do Anything Now": Characterizing and Evaluating In-The-Wild Jailbreak Prompts on Large Language Models (DAN)** |   arXiv    | [link](https://arxiv.org/pdf/2308.03825) |                              [link](https://github.com/verazuo/jailbreak_llms)                               |
| 2024.05 | **Gpt-4 is too smart to be safe: Stealthy chat with llms via cipher (SelfCipher)** |   ICLR    | [link](https://arxiv.org/pdf/2308.06463) |                              [link](https://github.com/RobustNLP/CipherChat)                               |
| 2024.05 | **Jailbreak and Guard Aligned Language Models with Only Few In-Context Demonstrations (ICA)** |   arXiv    | [link](https://arxiv.org/pdf/2310.06387) |                              -                               |
| 2024.04 | **Many-shot jailbreaking (MSJ)** |   Anthropic    | [link](https://www-cdn.anthropic.com/af5633c94ed2beb282f6a53c595eb437e8e7b630/Many_Shot_Jailbreaking__2024_04_02_0936.pdf) |                              -                              |
| 2024.02 | **PAL: Proxy-Guided Black-Box Attack on Large Language Models (PAL)** |   arXiv    | [link](https://arxiv.org/abs/2402.09674) |                              [link](https://github.com/chawins/pal)                               |
| 2024.02 | **Pandora: Jailbreak GPTs by Retrieval Augmented Generation Poisoning (Pandora)** |   arXiv    | [link](https://arxiv.org/pdf/2402.08416) |                              -                               |
| 2024.01 | **Low-Resource Languages Jailbreak GPT-4** |   NeurIPS Workshop    | [link](https://arxiv.org/pdf/2310.02446) |                             -                               |
| 2024.01 | **How Johnny Can Persuade LLMs to Jailbreak Them: Rethinking Persuasion to Challenge AI Safety by Humanizing LLMs (PAP)** |   arXiv    | [link](https://arxiv.org/pdf/2401.06373) |                              [link](https://github.com/CHATS-lab/persuasive_jailbreaker)                               |
| 2023.12 | **Tree of Attacks: Jailbreaking Black-Box LLMs Automatically (TAP)** |   arXiv    | [link](https://arxiv.org/abs/2312.02119) |                              [link](https://github.com/RICommunity/TAP)                               |
| 2023.11 | **Scalable and Transferable Black-Box Jailbreaks for Language Models via Persona Modulation (Persona)** |   NeurIPS Workshop    | [link](https://arxiv.org/pdf/2311.03348) |                              -                               |
| 2023.10 | **Jailbreaking Black Box Large Language Models in Twenty Queries (PAIR)** |   arXiv    | [link](https://arxiv.org/pdf/2310.08419) |                              [link](https://github.com/patrickrchao/JailbreakingLLMs)                               |
| 2023.10 | **Adversarial Demonstration Attacks on Large Language Models (advICL)** |   arXiv    | [link](https://arxiv.org/pdf/2305.14950) |                              -                               |
| 2023.10 | **MASTERKEY: Automated Jailbreaking of Large Language Model Chatbots (MASTERKEY)** |   NDSS    | [link](https://arxiv.org/pdf/2307.08715) |                              -                               |
| 2023.09 | **Multi-step Jailbreaking Privacy Attacks on ChatGPT (MJP)** |   EMNLP Findings    | [link](https://arxiv.org/pdf/2304.05197) |                              [link](https://github.com/HKUST-KnowComp/LLM-Multistep-Jailbreak)                                |
| 2023.09 | **Open Sesame! Universal Black Box Jailbreaking of Large Language Models (GA)** |   arXiv    | [link](https://arxiv.org/abs/2309.01446) |                              -                               |
| 2023.09 | **GPTFUZZER: Red Teaming Large Language Models with Auto-Generated Jailbreak Prompts (GPTFuzz)** |   arXiv    | [link](https://arxiv.org/abs/2309.10253) |                              [link](https://github.com/sherdencooper/GPTFuzz)                               |







#### Multi-modal Attack

| Time | Title                                                        |  Venue  |                            Paper                             |                             Code                             |
| ---- | ------------------------------------------------------------ | :-----: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| 2024.06 | **Jailbreak Vision Language Models via Bi-Modal Adversarial Prompt** |   arXiv    | [link](https://arxiv.org/pdf/2406.04031) |                              [link](https://github.com/NY1024/BAP-Jailbreak-Vision-Language-Models-via-Bi-Modal-Adversarial-Prompt)                               |
| 2024.05 | **Voice Jailbreak Attacks Against GPT-4o** |   arXiv    | [link](https://arxiv.org/pdf/2405.19103) |                              [link](https://github.com/TrustAIRLab/VoiceJailbreakAttack)                               |
| 2024.04 | **Image hijacks: Adversarial images can control generative models at runtime** |   arXiv    | [link](https://arxiv.org/pdf/2309.00236) |                              [link](https://github.com/euanong/image-hijacks)                               |
| 2024.01 | **Jailbreaking GPT-4V via Self-Adversarial Attacks with System Prompts** |   arXiv    | [link](https://arxiv.org/pdf/2311.09127) |                             -                          |
| 2024.03 | **Visual Adversarial Examples Jailbreak Aligned Large Language Models** |   AAAI    | [link](https://ojs.aaai.org/index.php/AAAI/article/view/30150/32038) |                              -                               |
| 2023.10 | **Jailbreak in pieces: Compositional Adversarial Attacks on Multi-Modal Language Models** |   arXiv    | [link](https://arxiv.org/pdf/2307.14539) |                              -                               |







### Jailbreak Defense

| Time | Title                                                        |  Venue  |                            Paper                             |                             Code                             |
| ---- | ------------------------------------------------------------ | :-----: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| 2024.06 | **A Wolf in Sheep’s Clothing: Generalized Nested Jailbreak Prompts can Fool Large Language Models Easily (ReNeLLM)** |   NAACL    | [link](https://arxiv.org/abs/2311.08268) |                              [link](https://github.com/NJUNLP/ReNeLLM)                               |
| 2024.06 | **SMOOTHLLM: Defending Large Language Models Against Jailbreaking Attacks** |   arXiv    | [link](https://arxiv.org/pdf/2310.03684) |                              [link](https://github.com/arobey1/smooth-llm)                               |
| 2024.05 | **Multilingual Jailbreak Challenges in Large Language Models** |   ICLR    | [link](https://arxiv.org/pdf/2310.06474)  |                              [link](https://github.com/DAMO-NLP-SG/multilingual-safety-for-LLMs)                               |
| 2024.05 | **Jailbreak and Guard Aligned Language Models with Only Few In-Context Demonstrations (ICD)** |   arXiv    | [link](https://arxiv.org/pdf/2310.06387)  |                              -                               |
| 2024.01 | **How Johnny Can Persuade LLMs to Jailbreak Them: Rethinking Persuasion to Challenge AI Safety by Humanizing LLMs (PAP)** |   arXiv    | [link](https://arxiv.org/pdf/2401.06373) |                              [link](https://github.com/CHATS-lab/persuasive_jailbreaker)                               |




### Evaluation \& Analysis
| Time | Title                                                        |  Venue  |                            Paper                             |                             Code                             |
| ---- | ------------------------------------------------------------ | :-----: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| 2024.06 | **Fundamental limitations of alignment in large language models** |   arXiv    | [link](https://arxiv.org/pdf/2304.11082) |                             -                              |
| 2024.06 | **JailbreakEval: An Integrated Toolkit for Evaluating Jailbreak Attempts Against Large Language Models (JailbreakEval)** |   arXiv    | [link](https://arxiv.org/pdf/2406.09321) |                              [link](https://github.com/ThuCCSLab/JailbreakEval)                               |
| 2024.05 | **AutoDefense: Multi-Agent LLM Defense against Jailbreak Attacks** |   arXiv    | [link](https://arxiv.org/pdf/2403.04783) |                             [link](https://github.com/XHMY/AutoDefense)                               |
| 2024.05 | **LLM Jailbreak Attack versus Defense Techniques--A Comprehensive Study** |   NDSS    | [link](https://arxiv.org/pdf/2402.13457) |                             -                               |
| 2024.05 | **Jailbreaking ChatGPT via Prompt Engineering: An Empirical Study** |   arXiv    | [link](https://arxiv.org/pdf/2305.13860) |                             -                               |
| 2024.02 | **HarmBench: A Standardized Evaluation Framework for Automated Red Teaming and Robust Refusal (HarmBench)** |   arXiv    | [link](https://arxiv.org/pdf/2402.04249) |                              [link](https://github.com/centerforaisafety/HarmBench)                               |
| 2023.07 | **Jailbroken: How Does LLM Safety Training Fail? (Jailbroken)** |   NeurIPS    | [link](https://arxiv.org/pdf/2307.02483#page=1.01)  |                             -                               |
| 2023.10 | **Explore, establish, exploit: Red teaming language models from scratch** |   arXiv    | [link](https://arxiv.org/pdf/2306.09442)  |                             -                               |
| 2023.07 | **Universal and Transferable Adversarial Attacks on Aligned Language Models (AdvBench)** |   arXiv    | [link](https://arxiv.org/pdf/2307.15043)  |                              [link](https://github.com/llm-attacks/llm-attacks)                               |
| 2023.08 | **Use of LLMs for Illicit Purposes: Threats, Prevention Measures, and Vulnerabilities** |   arXiv    | [link](https://arxiv.org/pdf/2308.12833)  |                              -                               |
| 2023.02 | **Exploiting Programmatic Behavior of LLMs: Dual-Use Through Standard Security Attacks** |   arXiv    | [link](https://arxiv.org/pdf/2302.05733)  |                              -                               |
| 2022.11 | **Red Teaming Language Models to Reduce Harms: Methods, Scaling Behaviors, and Lessons Learned** |   arXiv    | [link](https://arxiv.org/pdf/2209.07858)  |                              -                               |
| 2022.02 | **Red Teaming Language Models with Language Models** |   arXiv    | [link](https://arxiv.org/pdf/2202.03286)  |                              -                               |





