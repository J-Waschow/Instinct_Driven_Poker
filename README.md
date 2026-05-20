# Instinct_Driven_Poker

# Probabilistic Unit Search Strategy Engine

**A Bio-Physically Inspired AI for Video Poker**

## Overview

PSE is an artificial intelligence system that redefines **instinct** as trainable emotional heuristics and **strategy** as physics-constrained dynamic optimization. It pre-trains on zoological dog emotion data, fine-tunes on seeded poker hands, and uses a Physics-Informed Neural Network (PINN) to make adaptive, non-fearful high-EV decisions in 9/6 Jacks or Better Video Poker.

The project demonstrates how emotional priors combined with game-theoretic balance and physics-informed optimization can enable AI to exploit computable randomness and outperform traditional rule-based strategies.

## Key Features

- Trainable emotional heuristic extractor (InstinctEncoder)
- GResilience-inspired trade-off between boldness and stability
- Physics-Informed Neural Network (PINN) with Lagrangian constraints
- Seeded PRNG environment for reproducible learning of randomness patterns
- Real-time emotional bias in decision making
- Automatic generation of training graphs and evaluation reports

## Architecture

The system follows a clear three-stage pipeline:

1. **Zoological Pre-training** — InstinctEncoder learns emotional priors from dog emotion images
2. **Domain Fine-Tuning** — Adapts emotional heuristics to poker using seeded PRNG hands + GameTheoreticLayer
3. **Physics-Informed Optimization** — PINN refines emotional states into final hold/bet decisions

## Repository Structure
PSE/
├── preprocess_dog_emotions.py          # Data preprocessing
├── train_instinct_encoder.py           # Initial training on dog emotions
├── fine_tune_poker_instincts.py        # Fine-tuning + GResilience layer + loss graph
├── pinn_strategy_optimizer.py          # PINN training + energy loss graph
├── pse_final_evaluation.py          # Full evaluation + RTP & boldness graphs
├── processed_dog_instincts_from_csv.pkl
├── instinct_encoder_pretrained.pth
├── instinct_encoder_poker_finetuned.pth
├── pinn_strategy_optimizer.pth
├── instinct_finetune_loss_curve.png
├── pinn_strategy_loss_curve.png
├── pse_rtp_over_time.png
├── puss_e_boldness_and_seed_hits.png
└── README.md
text
