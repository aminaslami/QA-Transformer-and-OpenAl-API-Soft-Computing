# Question & Answering with Transfer Learning & OpenAl API 


### Lesson:  Soft-Computing


GPT Model: GPT3.5-Turbo

For **GPT3.5-Turbo** you should pay **$5.0 **Dollar, I think it's enough for 1 mounth

For this project total cost is just **$0.01** Dollar and **Total tokens** uese is **1540 Tokens**

It's very cheap to use.

![image](https://github.com/user-attachments/assets/0578eb7d-8c35-4ce2-8055-666683743600)

OpenAI API Key: https://platform.openai.com/api-keys


--------------------------------------------------------
My path directory in Google Colab: **Dataset**

      "/content/Firat-Uni-Fen-Bilimler-Enstitu-Soru-ve-Cevap-512-Rows.csv"

I runned the code on _T4 GPU_ (Google Colab),

Please select (change run type), be sure to select the _T4 GPU_


#### Ask this question when you run the code:

#### _BİLİM NEDİR_?  (WHAT IS SCIENCE?)

-------------------------------------------------------------------------
-------------------------------------------------------------------------
### Source: https://claude.ai/chat/
This how to chat with an AI tools or website.

_Write this prompt on Claud AI, you can get better response:_

**Prompt1:**
Write for question and aswering using transfer lerarning methot, the answer is get form csv file, and think like this, our csv file just have two columns and 500     rows. The prjcet is main api uses is openai api. Please help me dear Claud AI, You is the best.

Also add the cgpt-3.5-turbo model I want to use. And the code line be like 400 lines is better, Because want to get more beatiful projct. Use just python languge.    And thinks, this projct is run on google colab.

_**After that you get some problem please write the below prompt:**_

**Prompt2:**
Please separet this codes in different blocks, becaues it's a little confusing to undersantding.

Please don't write the .json file, and I don't need upload csv file, It's exist on colab.

-------------------------------------------------------------------------
-------------------------------------------------------------------------

The code output:

Transfer Learning QA System Initialization

**

API key set successfully.
Loaded data with 511 rows and 2 columns.
Columns: ['question', 'answer']
Available columns:
0: question
1: answer
After preprocessing: 502 rows

Initializing QA system...
Generating embeddings for all questions...
Generating embeddings: 100%
 16/16 [00:00<00:00, 49.55it/s]
Data split: 401 training examples, 101 test examples
OpenAI service initialized with model: gpt-3.5-turbo

QA System ready! Type 'quit' to exit, 'stats' to see statistics, or 'eval' to run evaluation.

Answer: 1-Bilim, doğal dünyayı ve evreni anlamak, açıklamak ve öngörmek için sistematik bir yaklaşım kullanan insan faaliyetidir.
2-Gözlem, deney ve mantıksal çıkarım yoluyla evren hakkında güvenilir bilgi edinme ve bu bilgiyi organize etme çabasıdır.

Processing time: 2.09s

Retrieved context:
1. Q: BİLİM NEDİR?
   A: 1-Bilim, doğal dünyayı ve evreni anlamak,
açıklamak ve öngörmek için sistematik bir
yaklaşım kullanan insan faaliyetidir.
2-Gözlem, deney ve mantıksal çıkarım yoluyla
evren hakkında güvenilir bilgi edinme ve bu
bilgiyi organize etme çabasıdır.
   Similarity: 1.0000
2. Q: BİLİMSEL YÖNTEM NEDİR?
   A: Bilimsel yöntem, bilim insanlarının doğal
fenomenleri incelemek, hipotezler oluşturmak, test etmek ve sonuçlara ulaşmak için kullandıkları sistematik bir yaklaşımdır.
   Similarity: 0.8421
3. Q: İSTATİSTİK NEDİR?
   A: İstatistik değişik anlamlarda kullanılan, bunun sonucu olarak
da farklı tanımları bulunan bir kavramdır. Quetelet isimli bir
istatistikçi 19. yüzyılda kavramın yüzden fazla tanımının
olduğunu belirlemiştir.
   Similarity: 0.7065
4. Q: BİLİM ETİĞİ
   A: Bilim etiği, etiğin bilimsel süreç içerisinde uygulanma
biçimidir. Bilim etiği, bilim erdemini anlama ve temelini
araştırmanın yanında bilim insanlarının bilimsel
araştırma sürecinin her aşamasında uyması gereken
etik ilke ve kuralları da belirler.
Bilim gibi etik de, kuralların eksik olduğu yerlerde
uygulamaya rehberlik etme ve kuralları
**
yorumlamanın ötesinde teorilere ve metodolojilere
dayanmaktadır.
   Similarity: 0.6883
6. Q: ARAŞTIRMA NEDİR?
   A: Belirli bir konu veya problem hakkında sistematik ve metodolojik bir inceleme sürecini ifade eder. Bilimsel araştırma, bilginin genişletilmesi, hipotezlerin test edilmesi ve yeni teorilerin geliştirilmesi amacıyla yapılır.
   Similarity: 0.6718

**
