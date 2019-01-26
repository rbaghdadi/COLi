The files in this folder are organized as follows:

    General
        clean.sh : remove some useless files.
        compile_and_run_mkldnn.sh : compile mkldnn code and run it. 
        configure.h: define size of input matrices.

    Tiramisu
        bn_layer_generator_tiramisu.cpp: Tiramisu code generator.

    Wrapper
        wrapper_nn.cpp: wrapped file that calls the code generated by Tiramisu.

    Intel MKLDNN
        bn_layer_generator_mkldnn.cpp: code that calls Intel MKL DNN batch normalization. 