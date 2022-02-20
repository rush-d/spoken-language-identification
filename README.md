# spoken-language-identification

Language Identification (LID) systems are used to classify the spoken language from a given audio sample and are typically the first step for many spoken language processing tasks, such as Automatic Speech Recognition (ASR) systems.

Dataset Used : VoxLingua107 : https://arxiv.org/abs/2011.12998
Webpage : http://bark.phon.ioc.ee/voxlingua107/

Dataset : VoxLingua107
Languages Selected : English, Hindi, Tamil, Bengali,Nepali,Malayalam,Kannada and Gujarati.

Max Duration = 14s
Min Duration = 4s
Average Duration = 7s

Previous Model : 4-layered Dense Neural Network Model
(Feed Forward Network)

Features Used : 13 MFCCs + 13 delta + 13 delta-delta coefficients(framewise) 
Training Accuracy  = 94.98 %
Test Accuracy = 31.75 %

Model : Convolutional Neural Network Model

Features Used : 13 MFCCs + 13 delta + 13 delta-delta coefficients(framewise) 
Training Accuracy  =  89.41 %
Test Accuracy =  69.94 %

Model : LSTM

Features Used : 13 MFCCs + 13 delta + 13 delta-delta coefficients(framewise) 
Training Accuracy  =  89.51 %
Test Accuracy =  54.69 %
