# 项目结构升级
next-gen-ai-scanner/
├── requirements.txt              # 新增ML依赖
├── config/
│   ├── models.yml               # 模型配置
│   └── payload_sources.yml      # Payload源配置
├── scanner/
│   ├── ai/
│   │   ├── ml_models/           # 机器学习模型
│   │   │   ├── payload_classifier.py
│   │   │   ├── anomaly_detector.py
│   │   │   └── vulnerability_predictor.py
│   │   ├── intelligence/        # 智能引擎
│   │   │   ├── threat_intelligence.py
│   │   │   └── attack_simulation.py
│   │   └── learning/            # 持续学习
│   │       ├── feedback_loop.py
│   │       └── knowledge_base.py
│   ├── detection/
│   │   ├── advanced/
│   │   │   ├── time_based.py
│   │   │   ├── boolean_based.py
│   │   │   └── second_order.py
│   │   └── heuristic/
│   │       ├── behavioral_analysis.py
│   │       └── pattern_recognition.py
│   ├── sources/
│   │   ├── cve_importer.py
│   │   ├── exploit_db.py
│   │   └── community_feed.py
│   └── reporting/
│       ├── html_reporter.py
│       ├── attack_graph.py
│       ├── remediation_advisor.py
│       └── executive_summary.py
