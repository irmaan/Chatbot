## Customer Support Chatbots based on tweets
Recently, there has been a considerable amount of excitement surrounding conversational chatbots due to their significant contribution in enhancing the overall customer experience. With the advent of chatbot technology, modern businesses have swiftly embraced the various capabilities and functionalities that chatbots offer, incorporating them into various processes to optimize their operations. As a result, the laborious and time-consuming task of filling out forms or transmitting information over the internet has now been greatly streamlined, thanks to the wide acceptance of conversational AIs. One of the most desirable attributes of an effective conversational chatbot lies in its ability to promptly respond to user requests while remaining cognizant of the current context in which the interaction is taking place. In this dynamic system, the key participants are the user, who initiates the interaction, and the chatbot, which serves as the intelligent counterpart, engaging in a dialogue with the user, providing relevant and helpful responses.

#### Dataset:
- Dataset can be downloaded via https://www.kaggle.com/thoughtvector/customer-support-on-twitter

#### Usage:

- python chatbot.py --max_vocab_size 50000 --max_seq_len 30 --embedding_dim 100 --hidden_state_dim 100 --epochs 80 --batch_size 128 --learning_rate 1e-4 --data_path /your_path_to_data/twcs.csv --outpath /your_output_folder/ --dropout 0.3 --mode train --num_train_records 50000 --version v1

- python chatbot.py --max_vocab_size 50000 --max_seq_len 30 --embedding_dim 100 --hidden_state_dim 100 --data_path /your_path_to_data/test.csv --outpath /your_output_folder/ --dropout 0.3 --mode inference --version v1 --load_model_from /your_deired_folder/s2s_model_v1_.h5 --vocabulary_path /your_deired_folder/vocabulary.pkl --reverse_vocabulary_path /your_deired_folder/reverse_vocabulary.pkl --count_vectorizer_path /your_deired_folder/count_vectorizer.pkl














 






