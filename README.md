# jetsoninfer_test

./imagenet-camera \
--prototxt=imgnet/deploy.prototxt \
--model=imgnet/snapshot_iter_134596.caffemodel \
--labels=imgnet/labels.txt \
--input_blob=data \
--output_blob=softmax

./imagenet-camera --prototxt=imgnet/deploy.prototxt --model=imgnet/snapshot_iter_134596.caffemodel --labels=imgnet/labels.txt --input_blob=data --output_blob=softmax


./detectnet-camera --prototxt=dnet/deploy.prototxt --model=dnet/snapshot_iter_3860.caffemodel --input_blob=data --output_cvg=coverage --output_bbox=bboxes

