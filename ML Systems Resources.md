MLOPs Software:

Book: https://www.manning.com/books/effective-data-science-infrastructure

Code from the book chapters can be found here: https://github.com/outerbounds/dsbook


We will discuss and compare a few tools available for MLOps: Airflow, MLflow, and MetaFlow

__MetaFlow__: Allows you to define a flow with multiple steps as a DAG. Each step can define the tasks to be done, artifacts (data) to be generated, metadata, and the next steps.
Your flow is independent of the compute and can run on different computing infrastructures with the help of an orchestrator.
You can monitor the metrics, performance, etc. of each of the steps.
You can debug, and re-execute the flow from the point where it stopped without having to re-run the time-consuming steps that executed successfully.


Excellent tutorials are available:
* https://docs.metaflow.org/introduction/metaflow-resources
* __Beginner:__ https://outerbounds.com/docs/data-science-welcome/
* __NLP:__ https://outerbounds.com/docs/nlp-tutorial-overview/
* __Computer Vision:__ https://outerbounds.com/docs/cv-tutorial-S2-overview/
* __Recommendation:__  https://outerbounds.com/docs/recsys-tutorial-S2-overview/


----------------------------------------------------------------

Once you have developed an ML model to solve a business problem, deploying and operating that is much more difficult than one would imagine!
The links below discuss why and how to overcome such problems. 
Notably, these topics are being discussed in mainstream leading ML and systems conferences as well. 
The best way to keep in touch is to regularly read research papers, systems blogs and resources such as below.


MLOPS links:
* https://neptune.ai/blog/recommender-systems-lessons-from-building-and-deployment: This blog is about of some of the key lessons from building and deploying recommender systems in the real world. You can learn about online metrics.
* https://eugeneyan.com/speaking/mlops-community-recsys/: Shows the offline and online architecture and how to generate recommendations at a low cost
* https://hktw-resources.awscloud.com/webinar-slides/introduction-to-mlops: AWS tools meant to simplify the deployment of ML models 

-------------------------------------------------------------------------


__9 step ML system design approach__

https://github.com/alirezadir/Machine-Learning-Interviews/blob/main/src/MLSD/ml-system-design.md


__Made with ML__: https://madewithml.com/

__Ray:__ 
Tutorial: https://github.com/anyscale/academy/blob/main/ray-serve/e2e/tutorial.ipynb

__Stanford MLSys Seminars__: https://www.youtube.com/playlist?list=PLSrTvUm384I9PV10koj_cqit9OfbJXEkq

__Visual Search System Design__: https://bytebytego.com/courses/machine-learning-system-design-interview/visual-search-system
