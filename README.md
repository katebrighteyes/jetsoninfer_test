# jetsoninfer_test

https://github.com/katebrighteyes/jetsoninfer_test

./imagenet \
--prototxt=imgnet/deploy.prototxt \
--model=imgnet/snapshot_iter_134596.caffemodel \
--labels=imgnet/labels.txt \
--input_blob=data \
--output_blob=softmax

./imagenet --prototxt=imgnet/deploy.prototxt --model=imgnet/snapshot_iter_134596.caffemodel --labels=imgnet/labels.txt --input_blob=data --output_blob=softmax


./detectnet --prototxt=dnet/deploy.prototxt --model=dnet/snapshot_iter_3860.caffemodel --input_blob=data --output_cvg=coverage --output_bbox=bboxes

git checkout 8b399c13e7998da2efd9d1d0ae6714356fd2e00e
