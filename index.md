## Selected projects in data science, machine learning, scheduling and operations research

---

### Agentic Forecasting Pipeline
End-to-end demand forecasting system combining statistical models, gradient-boosted trees, and foundation models into an optimized ensemble. The pipeline runs automated cross-validation across all model families, tunes ensemble weights via constrained optimization, and produces calibrated prediction intervals using conformal methods. Built for multi-SKU weekly forecasting with a production forecast step and a live interactive report.

Key components: StatsForecast (DOT, ADIDA, Croston), MLForecast with multiple LightGBM configs, Chronos-BOLT foundation models, conformal prediction intervals, and a model selection gate that enforces that only models beating the best baseline enter the ensemble.

<img src="images/forecasting_report_preview.png?raw=true" />

![](https://img.shields.io/badge/Python-white?logo=Python) ![](https://img.shields.io/badge/LightGBM-white?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAB0SURBVDhPY/hPIhg1SDcIDMbIAAAAABJRU5ErkJggg==) ![](https://img.shields.io/badge/StatsForecast-white) ![](https://img.shields.io/badge/MLForecast-white) ![](https://img.shields.io/badge/Conformal_Intervals-white) ![](https://img.shields.io/badge/Ensemble_Optimization-white)

[View interactive forecast report](https://teodor-georgiev.github.io/forecasting/)
