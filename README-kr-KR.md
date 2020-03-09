#하향식 학습법: 소프트웨어 엔지어를 위한 머신러닝

<p align="center">
  <a href="https://github.com/ZuzooVn/machine-learning-for-software-engineers">
    <img alt="Top-down learning path: Machine Learning for Software Engineers" src="https://img.shields.io/badge/Machine%20Learning-Software%20Engineers-blue.svg">
  </a>
  <a href="https://github.com/ZuzooVn/machine-learning-for-software-engineers/stargazers">
    <img alt="GitHub stars" src="https://img.shields.io/github/stars/ZuzooVn/machine-learning-for-software-engineers.svg">
  </a>
  <a href="https://github.com/ZuzooVn/machine-learning-for-software-engineers/network">
    <img alt="GitHub forks" src="https://img.shields.io/github/forks/ZuzooVn/machine-learning-for-software-engineers.svg">
  </a>
</p>

계기: [Coding Interview University](https://github.com/jwasham/coding-interview-university).

번역: [Brazilian Portuguese](https://github.com/ZuzooVn/machine-learning-for-software-engineers/blob/master/README-pt-BR.md) | [中文版本](https://github.com/ZuzooVn/machine-learning-for-software-engineers/blob/master/README-zh-CN.md) | [Français](https://github.com/ZuzooVn/machine-learning-for-software-engineers/blob/master/README-fr-FR.md) | [臺灣華語版本](https://github.com/ZuzooVn/machine-learning-for-software-engineers/blob/master/README-zh-TW.md)

[나(Nam Vu)의 머신러닝 엔지니어가 되기 위한 여정](https://www.codementor.io/zuzoovn/how-i-plan-to-become-a-machine-learning-engineer-a4metbcuk)

## 이 글에 대해

이 글은 내가 모바일 엔지니어에서 머신러닝 엔지니어가 되기 위해 계획한 공부 방법입니다. (혼자 학습, 컴퓨터 과학  x)

입문자를 위해 기초적인 수학 배경 지식과 실습을 통한 학습으로 머신러닝을 공부할 수 있도록 구성하였습니다.
따라서 기존의 학습 방식과는 다르게, 이러한 머신러닝 공부법은 결과 지향적이며 하향식 구조로 구성되어 있습니다.

더 발전시킬 부분이 있으면 언제든 참여하시면 되겠습니다.

---

## 목차

- [이 글에 대해](#이-글에-대해)
- [왜 사용하는가](#why-use-it)
- [어떻게 사용할 것인가](#how-to-use-it)
- [저자 정보](#follow-me)
- [똑똑하지 않다고 생각할 필요 없다](#dont-feel-you-arent-smart-enough)
- [비디오 자료에 대해](#about-video-resources)
- [전제 지식](#prerequisite-knowledge)
- [일일계획](#the-daily-plan)
- [동기부여](#motivation)
- [머신러닝 개요](#machine-learning-overview)
- [머신러닝 정복하기](#machine-learning-mastery)
- [머신러닝=재미](#machine-learning-is-fun)
- [Inky Machine Learning](#inky-machine-learning)
- [머신러닝: 세부 가이드](#machine-learning-an-in-depth-guide)
- [기타 이야기 및 경험](#stories-and-experiences)
- [머신러닝 알고리즘](#machine-learning-algorithms)
- [초보자를 위한 책](#beginner-books)
- [실용책](#practical-books)
- [Kaggle에서 지식 경쟁](#kaggle-knowledge-competitions)
- [비디오 시리즈](#video-series)
- [MOOC](#mooc)
- [기타 자료](#resources)
- [오픈 소스 기여자가 되기 위해](#becoming-an-open-source-contributor)
- [게임](#games)
- [팟캐스트](#podcasts)
- [커뮤니티](#communities)
- [컨퍼런스](#conferences)
- [인터뷰 질문들](#interview-questions)
- [내 꿈의 직장](#my-admired-companies)

---

## Why use it?

I'm following this plan to prepare for my near-future job: Machine learning engineer. I've been building native mobile applications (Android/iOS/Blackberry) since 2011. I have a Software Engineering degree, not a Computer Science degree. I have an itty-bitty amount of basic knowledge about: Calculus, Linear Algebra, Discrete Mathematics, Probability & Statistics from university.
Think about my interest in machine learning:
- [Can I learn and get a job in Machine Learning without studying CS Master and PhD?](https://www.quora.com/Can-I-learn-and-get-a-job-in-Machine-Learning-without-studying-CS-Master-and-PhD)
    - *"You can, but it is far more difficult than when I got into the field."* [Drac Smith](https://www.quora.com/Can-I-learn-and-get-a-job-in-Machine-Learning-without-studying-CS-Master-and-PhD/answer/Drac-Smith?srid=oT0p)
- [How do I get a job in Machine Learning as a software programmer who self-studies Machine Learning, but  never has a chance to use it at work?](https://www.quora.com/How-do-I-get-a-job-in-Machine-Learning-as-a-software-programmer-who-self-studies-Machine-Learning-but-never-has-a-chance-to-use-it-at-work)
    - *"I'm hiring machine learning experts for my team and your MOOC will not get you the job (there is better news below). In fact, many people with a master's in machine learning will not get the job because they (and most who have taken MOOCs) do not have a deep understanding that will help me solve my problems."* [Ross C. Taylor](https://www.quora.com/How-do-I-get-a-job-in-Machine-Learning-as-a-software-programmer-who-self-studies-Machine-Learning-but-never-has-a-chance-to-use-it-at-work/answer/Ross-C-Taylor?srid=oT0p)
- [What skills are needed for machine learning jobs?](http://programmers.stackexchange.com/questions/79476/what-skills-are-needed-for-machine-learning-jobs)
    - *"First, you need to have a decent CS/Math background. ML is an advanced topic so most textbooks assume that you have that background. Second, machine learning is a very general topic with many sub-specialties requiring unique skills. You may want to browse the curriculum of an MS program in Machine Learning to see the course, curriculum and textbook."* [Uri](http://softwareengineering.stackexchange.com/a/79717)
    - *"Probability, distributed computing, and Statistics."* [Hydrangea](http://softwareengineering.stackexchange.com/a/79575)

I find myself in times of trouble.

AFAIK, [There are two sides to machine learning](http://machinelearningmastery.com/programmers-can-get-into-machine-learning/):
- Practical Machine Learning: This is about querying databases, cleaning data, writing scripts to transform data and gluing algorithm and libraries together and writing custom code to squeeze reliable answers from data to satisfy difficult and ill-defined questions. It’s the mess of reality.
- Theoretical Machine Learning: This is about math and abstraction and idealized scenarios and limits and beauty and informing what is possible. It is a whole lot neater and cleaner and removed from the mess of reality.

I think the best way for practice-focused methodology is something like ['practice — learning — practice'](http://machinelearningmastery.com/machine-learning-for-programmers/#comment-358985), that means where students first come with some existing projects with problems and solutions (practice) to get familiar with traditional methods in the area and perhaps also with their methodology. After practicing with some elementary experiences, they can go into the books and study the underlying theory, which serves to guide their future advanced practice and will enhance their toolbox of solving practical problems. Studying theory also further improves their understanding on the elementary experiences, and will help them acquire advanced experiences more quickly.

 It's a long plan. It's going to take me years. If you are familiar with a lot of this already it will take you a lot less time.
