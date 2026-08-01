# Jarvis

> Personal AI companion — 贾维斯，一个带人格、有记忆、能主动服务的个人 AI 助手。

## 愿景

从 CLI 走向多通道（语音 + App/Web），从被动响应走向主动关怀，从单一工具走向机器人 + 智能家居的统一大脑。

## 技术栈

| 层 | 技术 |
|---|---|
| 大脑 | Hermes Agent + DeepSeek/Kimi (云端 LLM) |
| 机器人 | Telos (ROS2 + STM32) |
| 智能家居 | Home Assistant |
| 语音 | VAD (本地) + STT (云端) + TTS |
| 交互 | Telegram / CLI / 语音 / Web |
| 网络 | Tailscale |

## 路线图

- [ ] Phase 1: Telegram 通道打通
- [ ] Phase 2: 贾维斯人格 + 长期记忆升级
- [ ] Phase 3: 语音通道 (STT + TTS)
- [ ] Phase 4: HA 深度整合 (主动感知)
- [ ] Phase 5: 机器人控制接入 (Telos)

## 文档

所有设计文档在 `docs/` 下。
