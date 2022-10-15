2022-10-13 03:56:46.315709: I tensorflow/core/platform/cpu_feature_guard.cc:193] This TensorFlow binary is optimized with oneAPI Deep Neural Network Library (oneDNN) to use the following CPU instructions in performance-critical operations:  AVX AVX2
To enable them in other operations, rebuild TensorFlow with the appropriate compiler flags.
2022-10-13 03:56:46.681204: I tensorflow/core/common_runtime/gpu/gpu_device.cc:1616] Created device /job:localhost/replica:0/task:0/device:GPU:0 with 9491 MB memory:  -> device: 0, name: NVIDIA GeForce RTX 3060, pci bus id: 0000:08:00.0, compute capability: 8.6
WARNING:tensorflow:From d:\Windows Only\GIT\Tensorflow Object Detection\TFODCourse\tfod\lib\site-packages\tensorflow\python\autograph\impl\api.py:458: calling map_fn_v2 (from tensorflow.python.ops.map_fn) with back_prop=False is deprecated and will be removed in a future version.
Instructions for updating:
back_prop=False is deprecated. Consider using tf.stop_gradient instead.
Instead of:
results = tf.map_fn(fn, elems, back_prop=False)
Use:
results = tf.nest.map_structure(tf.stop_gradient, tf.map_fn(fn, elems))
W1013 03:56:48.812482 16012 deprecation.py:623] From d:\Windows Only\GIT\Tensorflow Object Detection\TFODCourse\tfod\lib\site-packages\tensorflow\python\autograph\impl\api.py:458: calling map_fn_v2 (from tensorflow.python.ops.map_fn) with back_prop=False is deprecated and will be removed in a future version.
Instructions for updating:
back_prop=False is deprecated. Consider using tf.stop_gradient instead.
Instead of:
results = tf.map_fn(fn, elems, back_prop=False)
Use:
results = tf.nest.map_structure(tf.stop_gradient, tf.map_fn(fn, elems))
WARNING:tensorflow:Skipping full serialization of Keras layer <object_detection.meta_architectures.ssd_meta_arch.SSDMetaArch object at 0x0000019EB0F4ADF0>, because it is not built.
W1013 03:57:01.082589 16012 save_impl.py:66] Skipping full serialization of Keras layer <object_detection.meta_architectures.ssd_meta_arch.SSDMetaArch object at 0x0000019EB0F4ADF0>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <keras.layers.convolutional.separable_conv2d.SeparableConv2D object at 0x000001A1800BF0A0>, because it is not built.
W1013 03:57:01.224784 16012 save_impl.py:66] Skipping full serialization of Keras layer <keras.layers.convolutional.separable_conv2d.SeparableConv2D object at 0x000001A1800BF0A0>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x000001A180097F70>, because it is not built.
W1013 03:57:01.224784 16012 save_impl.py:66] Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x000001A180097F70>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x000001A180089F70>, because it is not built.
W1013 03:57:01.224784 16012 save_impl.py:66] Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x000001A180089F70>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <keras.layers.convolutional.separable_conv2d.SeparableConv2D object at 0x000001A1801062E0>, because it is not built.
W1013 03:57:01.224784 16012 save_impl.py:66] Skipping full serialization of Keras layer <keras.layers.convolutional.separable_conv2d.SeparableConv2D object at 0x000001A1801062E0>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x000001A180106430>, because it is not built.
W1013 03:57:01.224784 16012 save_impl.py:66] Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x000001A180106430>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x000001A1801063D0>, because it is not built.
W1013 03:57:01.224784 16012 save_impl.py:66] Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x000001A1801063D0>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <keras.layers.convolutional.separable_conv2d.SeparableConv2D object at 0x000001A180106C70>, because it is not built.
W1013 03:57:01.224784 16012 save_impl.py:66] Skipping full serialization of Keras layer <keras.layers.convolutional.separable_conv2d.SeparableConv2D object at 0x000001A180106C70>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x000001A180106BE0>, because it is not built.
W1013 03:57:01.224784 16012 save_impl.py:66] Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x000001A180106BE0>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x000001A180093670>, because it is not built.
W1013 03:57:01.224784 16012 save_impl.py:66] Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x000001A180093670>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <keras.layers.convolutional.separable_conv2d.SeparableConv2D object at 0x000001A180093C70>, because it is not built.
W1013 03:57:01.224784 16012 save_impl.py:66] Skipping full serialization of Keras layer <keras.layers.convolutional.separable_conv2d.SeparableConv2D object at 0x000001A180093C70>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x000001A180093700>, because it is not built.
W1013 03:57:01.224784 16012 save_impl.py:66] Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x000001A180093700>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x000001A180093DC0>, because it is not built.
W1013 03:57:01.224784 16012 save_impl.py:66] Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x000001A180093DC0>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x000001A180133460>, because it is not built.
W1013 03:57:01.225783 16012 save_impl.py:66] Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x000001A180133460>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x000001A180084070>, because it is not built.
W1013 03:57:01.225783 16012 save_impl.py:66] Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x000001A180084070>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x000001A1800B4A60>, because it is not built.
W1013 03:57:01.225783 16012 save_impl.py:66] Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x000001A1800B4A60>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x000001A1800B4A30>, because it is not built.
W1013 03:57:01.225783 16012 save_impl.py:66] Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x000001A1800B4A30>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x000001A18010E070>, because it is not built.
W1013 03:57:01.225783 16012 save_impl.py:66] Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x000001A18010E070>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x000001A18010E220>, because it is not built.
W1013 03:57:01.225783 16012 save_impl.py:66] Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x000001A18010E220>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x000001A18010EE80>, because it is not built.
W1013 03:57:01.225783 16012 save_impl.py:66] Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x000001A18010EE80>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x000001A18010E5E0>, because it is not built.
W1013 03:57:01.225783 16012 save_impl.py:66] Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x000001A18010E5E0>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x000001A18005FFA0>, because it is not built.
W1013 03:57:01.225783 16012 save_impl.py:66] Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x000001A18005FFA0>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x000001A18005FA60>, because it is not built.
W1013 03:57:01.225783 16012 save_impl.py:66] Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x000001A18005FA60>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x000001A180099AC0>, because it is not built.
W1013 03:57:01.225783 16012 save_impl.py:66] Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x000001A180099AC0>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x000001A180099D90>, because it is not built.
W1013 03:57:01.225783 16012 save_impl.py:66] Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x000001A180099D90>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x000001A1800991C0>, because it is not built.
W1013 03:57:01.225783 16012 save_impl.py:66] Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x000001A1800991C0>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x000001A180099850>, because it is not built.
W1013 03:57:01.225783 16012 save_impl.py:66] Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x000001A180099850>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x000001A180099FD0>, because it is not built.
W1013 03:57:01.225783 16012 save_impl.py:66] Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x000001A180099FD0>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x000001A180099370>, because it is not built.
W1013 03:57:01.225783 16012 save_impl.py:66] Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x000001A180099370>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x0000019EF5201760>, because it is not built.
W1013 03:57:01.225783 16012 save_impl.py:66] Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x0000019EF5201760>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x0000019F062F88E0>, because it is not built.
W1013 03:57:01.225783 16012 save_impl.py:66] Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x0000019F062F88E0>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x000001A18009E5B0>, because it is not built.
W1013 03:57:01.225783 16012 save_impl.py:66] Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x000001A18009E5B0>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x0000019F064F6070>, because it is not built.
W1013 03:57:01.225783 16012 save_impl.py:66] Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x0000019F064F6070>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x0000019EBEE44490>, because it is not built.
W1013 03:57:01.225783 16012 save_impl.py:66] Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x0000019EBEE44490>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x0000019EBEE44F10>, because it is not built.
W1013 03:57:01.226782 16012 save_impl.py:66] Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x0000019EBEE44F10>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x0000019EB24B5E50>, because it is not built.
W1013 03:57:01.226782 16012 save_impl.py:66] Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x0000019EB24B5E50>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x0000019EB24B5E20>, because it is not built.
W1013 03:57:01.226782 16012 save_impl.py:66] Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x0000019EB24B5E20>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x0000019F147BF070>, because it is not built.
W1013 03:57:01.226782 16012 save_impl.py:66] Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x0000019F147BF070>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x0000019F147BF430>, because it is not built.
W1013 03:57:01.226782 16012 save_impl.py:66] Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x0000019F147BF430>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x0000019F062F61F0>, because it is not built.
W1013 03:57:01.226782 16012 save_impl.py:66] Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x0000019F062F61F0>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x0000019F062F6790>, because it is not built.
W1013 03:57:01.226782 16012 save_impl.py:66] Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x0000019F062F6790>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x0000019F00319100>, because it is not built.
W1013 03:57:01.226782 16012 save_impl.py:66] Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x0000019F00319100>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x0000019F00319520>, because it is not built.
W1013 03:57:01.226782 16012 save_impl.py:66] Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x0000019F00319520>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x0000019F147C2D00>, because it is not built.
W1013 03:57:01.226782 16012 save_impl.py:66] Skipping full serialization of Keras layer <object_detection.core.freezable_batch_norm.FreezableBatchNorm object at 0x0000019F147C2D00>, because it is not built.
WARNING:tensorflow:Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x0000019F01B7ED60>, because it is not built.
W1013 03:57:01.226782 16012 save_impl.py:66] Skipping full serialization of Keras layer <keras.layers.core.lambda_layer.Lambda object at 0x0000019F01B7ED60>, because it is not built.
W1013 03:57:10.669641 16012 save.py:269] Found untraced functions such as WeightSharedConvolutionalBoxPredictor_layer_call_fn, WeightSharedConvolutionalBoxPredictor_layer_call_and_return_conditional_losses, WeightSharedConvolutionalBoxHead_layer_call_fn, WeightSharedConvolutionalBoxHead_layer_call_and_return_conditional_losses, WeightSharedConvolutionalClassHead_layer_call_fn while saving (showing 5 of 173). These functions will not be directly callable after loading.
INFO:tensorflow:Assets written to: Tensorflow\workspace\models\my_ssd_mobnet\export\saved_model\assets
I1013 03:57:14.279848 16012 builder_impl.py:779] Assets written to: Tensorflow\workspace\models\my_ssd_mobnet\export\saved_model\assets
INFO:tensorflow:Writing pipeline config file to Tensorflow\workspace\models\my_ssd_mobnet\export\pipeline.config
I1013 03:57:15.067907 16012 config_util.py:253] Writing pipeline config file to Tensorflow\workspace\models\my_ssd_mobnet\export\pipeline.config
