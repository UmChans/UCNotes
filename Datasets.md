## MagicHub（magichub.com）
MagicHub 是由 Magic Data Technology（北京晴数智慧科技有限公司） 运营的开源数据集社区。

- 热门数据集（按下载量排序）  
ASR-RAMC-BigCCSC：中文对话语音语料库  
Multi-Modal Driver Behaviors Dataset for DMS：驾驶员行为多模态数据集  
ASR-SCCantDuSC：粤语日常语音语料库  
ASR-SCSichDiaDuSC：四川话日常语音语料库  
ASR-EgArbCSC：埃及阿拉伯语对话语音语料库  
MAGICDATA-DUPLEX-KOREAN / SPANISH：全双工对话语音数据集（韩语/西语，新发布）  
还有上海话、重庆12城市方言、粤语/Wu 方言 TTS 等数据集  
- 覆盖领域  
行业：金融服务、汽车、社交、智能家居、智能终端设备  
场景：在线客服、线下销售、智能座舱、短视频、聊天、智能设备  
- 与你的工作的关联  
结合你之前提到的闻诊数据建设，MagicHub 上有一些值得关注的资源：  
中文对话语音语料库（BigCCSC） — 包含真实对话场景的录音，可能包含不同音质条件的样本  
多方言数据集 — 如果你的闻诊涉及不同地区人群  
全双工对话数据集 — 包含重叠语音等复杂声学场景  

MagicHub 的 MAGICDATA-DUPLEX 全双工对话语料系列覆盖 5 个语种。公开版本如下：
| 语种 | 数据集与下载入口 | 公开时长 |
|---|---|---:|
| 中文普通话 | [Multi-stream Spontaneous Conversation Training Datasets_Chinese](https://huggingface.co/datasets/MagicHub/multi-stream-spontaneous-conversation-training-datasets_chinese) | 10 小时 |
| 英语 | [Multi-stream Spontaneous Conversation Training Datasets_English](https://huggingface.co/datasets/MagicHub/multi-stream-spontaneous-conversation-training-datasets_english) | 5 小时 |
| 日语 | [Japanese Duplex Conversation Training Dataset](https://magichub.com/datasets/japanese-duplex-conversation-training-dataset/) | 10.35 小时 |
| 韩语 | [MAGICDATA-DUPLEX-KOREAN](https://magichub.com/datasets/mdt-duplex-korean-training-dataset/) | 10 小时 |
| 西班牙语 | [MAGICDATA-DUPLEX-SPANISH](https://magichub.com/datasets/mdt-duplex-spanish-training-dataset/) | 10 小时 |

这些语料的核心特点是：真人自然对话、双方独立音轨，保留重叠说话、打断、简短应答和停顿，适合研究话轮预测、打断检测及实时语音交互。系列采用 16 kHz、16 bit WAV，配套转写和相关标注。  
注意，表中是公开子集规模，商业全量语料需另行获取。授权也应按实际下载版本核对：中英文官方 Hugging Face 数据卡明确注明仅限学术研究、不可商用；公开下载不代表可以直接用于商业训练。