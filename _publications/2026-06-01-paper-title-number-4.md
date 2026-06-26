---
title: "Zelda: Feedback-driven Closed-box Fuzzing for Identifying Web Application Vulnerabilities"
collection: publications
category: conferences
permalink: /publication/2026-06-25-paper-title-number-4
date: 2026-06-25
venue: 'WWW&apos;26'
author: "Soyoung Lee, Sunnyeo Park, Yonghwi Kwon, Sooel Son"
paperurl: "https://dl.acm.org/doi/pdf/10.1145/3774904.3792378"
posterurl: 
abstract: "Despite its practical impact, closed-box fuzzing on web applications remains understudied. This paper investigates two fundamental limitations of closed-box web fuzzing: (1) limited input space exploration due to the lack of a feedback mechanism, and (2) ineffective exploitation strategies caused by the shallow vulnerability identification. We propose Zelda, a novel closed-box web fuzzer designed to address these limitations. Specifically, we infer feedback signals from web responses in a closed-box testing environment, thereby deriving a feedback mechanism to guide the fuzzing process. We then coordinate two distinct input generation strategies for path exploration and exploitation, based on the exploration stage, which facilitates both in-page code coverage and vulnerability identification. Our evaluation across 15 real-world applications and nine benchmark sets demonstrates that Zelda's feedback mechanism and strategies are effective in practical web vulnerability discovery. Zelda uncovered 182 vulnerabilities, outperforming six state-of-the-art web fuzzers. In the wild, Zelda further discovered previously unreported vulnerabilities that received 29 CVE assignments."
---
