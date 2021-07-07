# bert-android_stack
Notebooks, results and dataset on android dataset

## Baseline
Contains all the baseline notebook with the saved output trained on android dataset and their traces (Model loss, accuracy on train) (related+linked)

Note : Evaluator Section of the code in the notebooks contains some bug and are fork of sentence-transformer evaluators

1. BERT_Only.ipynb(unimodal): BERT Bi-encoder, passing title+tag+body as an input
2. BERT_Only+Tags(unimodal): (BERT + BiLSTM) Bi-encoder,passing title+body to the bert and tag into BiLSTM
3. BERT_BERT.ipynb(unimodal): (BERT+BERT) Bi-encoder, passing title+body to one BERT and tags to another BERT
4. RESNET+BERT(multimodal): Resnet + BERT, passing title+tag+body as an input to BERT and images to RESNET and concat both
5.	Image Pairs Related.docx: Contains stats about number of images and non images pair in train,dev and test
6. USE_Baseline: Contains the baseline using Universal sentence encoder 

## MultiModal
1. Multimodal_final.ipynb : Final multimodal notebook consists of model implemented in Xinyu paper, with optimized dataset spilliting and exclusivity in dev,test and train
2. Multimodal_1.ipynb : Multimodal notebook with simple dataset splitting

## sbert
Contains models and notebooks implemented using sbert library in a bi-encoder way. Losses and accuracy function are inspired from their sbert implementation on quora related pair dataset
(Check the paths to the dataset before running)

## Google-Drive
1. all_data_softmax_3epoch_model:Contains saved sentence-transformer model (using sbert lib) trained on combining all the datasets available (related only)
2. Linked_android_model(cross_encoder): Contains the result of training an cross encoder (sentence transformer) on linked dataset
3. Linked: Contains all the baseline evaluated on linked dataset seperately
4. MultiModal: Contains the multimodal notebooks, data splits for android and saved models and traces of different experiment
5. quora_android_2: Contains the sbert model based on BERT and distill-bert with different margins, losses and accuracy. 
6. quora_android(bad_data_splitting): Contains a buggy implementation of data spliiting. May contains some useful functions
7. quora_apple: Contains the notebook of sbert folder, implemented on apple dataset
8. preproccesed_data : Contains all the pre-proccesed data; nosw: no stop words, l: linked
9. SemEval 2017 task 3 dataset: Contains research on community-based QA forums
10. Shah(2018): SOTA model (before bert) on android, superuser etc.
11. USE_Baseline.ipynb: Baseline constructed using universal sentence encoder

	
