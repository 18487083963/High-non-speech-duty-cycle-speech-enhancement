# 1、compose and detect(Matlab)

file:compose and detect

main:

make_train_noisy:compose train data

make_unusuall_test:compose test data

enhance_test: test the data that detected by prior and enhanced by GAN

function:

others are sub-function

# 2、speech detection based on prior feature stream(Matlab 2017a) 

file: prior feature stream

main:

vo_detect: speech detecion  based on prior feature stream and detect the performance.

compose:to display the detecte result of different speech detection method. 

function:

others are sub-function

# 3、GAN

main:

kaggle:the GAN trained based on kaggle platform

data_process/Dataset/model/   are the module of GAN. main is the main funtion of those module.

test:to enhance the reconstruct audio segment by prior feature stream. 

# 4、data

serialized_train_data:train data for GAN(account for the restrict,there just give some demo,more data in there:https://www.kaggle.com/lanyangyang123/serialized-train-data)

unusuall_test（-5dB）/unusuall_clean  are the pairs of test data

detected(prior feature stream):detected by prior feature stream

enhanced:the reconstruct audio segment by prior feature stream and enhanced by GAN 

(there just give some example,more data and detail to reference the paper"**High non-speech duty cycle speech enhancement based on prior feature** **stream** **and generati****ve** **a****dversarial** **network****(GAN)**",author:MingLiang Yang)
