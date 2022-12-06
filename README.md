
![image](images/img.png)


# E2E Question Answering Task

- When looking at a question on the internet, you will receive numerous answers, but not the straight information you may need. An End-to-end Question Answering System aims at satisfying users who are looking to answer a specific question, especially by giving a direct answer to that question.

- In this challenge, participants build a system that can find an answer for each given question in the Vietnamese Wikipedia Corpus. The answer may be a Wikipedia entity (represented by a Wikipedia Page) or a number or a date.

## Input & Output:

**Question**: A question (in Vietnamese)

**Answer**: A Wikipedia entity, a number, or a date in the Wikipedia corpus.


- If the answer is a Wikipedia entity the answer should start with “wiki/” and the title of the page, using “_” instead of “ “ space. For examples: “wiki/George_Washington”, “wiki/George_Washington”, "wiki/Ngô_Viết_Thụ"
- If the answer is a date, the answer should follow the format “ngày … tháng … năm ...“, “tháng … năm …", “năm ….”. For examples: năm 1942, ngày 2 tháng 9 năm 1945.
- If the answer is a number, the answer should be a literal number: For example: “15”, “16”

## Examples 

| Question | Expected Answer |
| --- | --- |
| Ai là người thiết kế ra dinh độc lập ?	 | wiki/Ngô_Viết_Thụ |
| Tổng thống đầu tiên của Mỹ là ai ? | wiki/George_Washington |
| Nhà thơ Xuân Quỳnh sinh năm bao nhiêu ? | năm 1942 |
| Đại Việt sử ký toàn thư của Ngô Sĩ Liên năm 1479 gồm bao nhiêu quyển | 15 | 
| Nước nào vô địch World Cup 2026	| null |	
	
Although there are many questions which may have multiple answers, in the challenge we focus on questions that have only one single answer.
	
