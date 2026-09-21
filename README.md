# Git Practice

## Article

[Software Engineering for Self-Adaptive Robotics: A Research Agenda](https://doi.org/10.1145/3828754)

## My thoughts

What I find most interesting is that self-adaptive robots change where software engineering ends. For normal software, we can test the code before deployment and assume the environment is relatively stable. A robot cannot make this assumption because its environment, sensors, and even its own behavior can change during operation. This means testing should continue after deployment. In practice, robotic systems may need continuous monitoring, simulation-based testing, safe fallback behaviors, and ways to roll back a bad model or policy. I think this extends ideas such as CI/CD from software into the physical world. The important problem is therefore not only making robots more intelligent, but also making their changing behavior observable, testable, and recoverable.
