package(default_visibility = ["//visibility:public"])

load("@org_tensorflow_tensorboard//tensorboard/defs:web.bzl", "tf_web_library")
load("@org_tensorflow_tensorboard//tensorboard/defs:vulcanize.bzl", "tensorboard_html_binary")

licenses(["notice"])  # Apache 2.0

tf_web_library(
    name = "multidemo",
    testonly = True,
    srcs = [
        "multi_index.html",
        "wit-multi-demo.html",
        "@org_tf_tfjs//:tf.min.js",
    ] + glob(["data/**"]),
    path = "/wit-dashboard",
    deps = [
        "@org_tensorflow_tensorboard//tensorboard/components/tf_imports:polymer",
        "//wit_dashboard",
    ],
)

tensorboard_html_binary(
    name = "multidemoserver",
    testonly = True,  # Keeps JavaScript somewhat readable
    compile = True,  # Run Closure Compiler
    input_path = "/wit-dashboard/multi_index.html",
    output_path = "/wit-dashboard/multi_demo.html",
    deps = [":multidemo"],
)

############################################################################################################
tf_web_library(
    name = "demo",
    testonly = True,
    srcs = [
        "index.html",
        "wit-demo.html",
        "@org_tf_tfjs//:tf.min.js",
    ] + glob(["data/**"]),
    path = "/wit-dashboard",
    deps = [
        "@org_tensorflow_tensorboard//tensorboard/components/tf_imports:polymer",
        "//wit_dashboard",
    ],
)

tensorboard_html_binary(
    name = "demoserver",
    testonly = True,  # Keeps JavaScript somewhat readable
    compile = True,  # Run Closure Compiler
    input_path = "/wit-dashboard/index.html",
    output_path = "/wit-dashboard/demo.html",
    deps = [":demo"],
)
############################################################################################################
tf_web_library(
    name = "imagedemo",
    testonly = True,
    srcs = [
        "image_index.html",
        "wit-image-demo.html",
        "@org_tf_tfjs//:tf.min.js",
        "@org_tf_tfjs_mobilenet//:mobilenet.js",
    ] + glob(["data/**"]),
    path = "/wit-dashboard",
    deps = [
        "@org_tensorflow_tensorboard//tensorboard/components/tf_imports:polymer",
        "//wit_dashboard",
    ],
)

tensorboard_html_binary(
    name = "imagedemoserver",
    testonly = True,  # Keeps JavaScript somewhat readable
    compile = True,  # Run Closure Compiler
    input_path = "/wit-dashboard/image_index.html",
    output_path = "/wit-dashboard/image_demo.html",
    deps = [":imagedemo"],
)

####################################################################################
tf_web_library(
    name = "pneumoniademo",
    testonly = True,
    srcs = [
        "pneumonia_index.html",
        "wit-pneumonia-demo.html",
        "@org_tf_tfjs//:tf.min.js",
        "@org_tf_tfjs_mobilenet//:mobilenet.js",
    ] + glob(["data/**"]),
    path = "/wit-dashboard",
    deps = [
        "@org_tensorflow_tensorboard//tensorboard/components/tf_imports:polymer",
        "//wit_dashboard",
    ],
)

tensorboard_html_binary(
    name = "pneumoniademoserver",
    testonly = True,  # Keeps JavaScript somewhat readable
    compile = True,  # Run Closure Compiler
    input_path = "/wit-dashboard/pneumonia_index.html",
    output_path = "/wit-dashboard/pneumonia_demo.html",
    deps = [":pneumoniademo"],
)

#########################################################################################

tf_web_library(
    name = "GIDiseasedemo",
    testonly = True,
    srcs = [
        "GIDisease_index.html",
        "wit-GIDisease-demo.html",
        "@org_tf_tfjs//:tf.min.js",
        "@org_tf_tfjs_mobilenet//:mobilenet.js",
    ] + glob(["data/**"]),
    path = "/wit-dashboard",
    deps = [
        "@org_tensorflow_tensorboard//tensorboard/components/tf_imports:polymer",
        "//wit_dashboard",
    ],
)

tensorboard_html_binary(
    name = "GIDiseasedemoserver",
    testonly = True,  # Keeps JavaScript somewhat readable
    compile = True,  # Run Closure Compiler
    input_path = "/wit-dashboard/GIDisease_index.html",
    output_path = "/wit-dashboard/GIDisease_demo.html",
    deps = [":GIDiseasedemo"],
)
#########################################################################################

tf_web_library(
    name = "covid19xraydemo",
    testonly = True,
    srcs = [
        "covid19xray_index.html",
        "wit-covid19xray-demo.html",
        "@org_tf_tfjs//:tf.min.js",
        "@org_tf_tfjs_mobilenet//:mobilenet.js",
    ] + glob(["data/**"]),
    path = "/wit-dashboard",
    deps = [
        "@org_tensorflow_tensorboard//tensorboard/components/tf_imports:polymer",
        "//wit_dashboard",
    ],
)

tensorboard_html_binary(
    name = "covid19xraydemoserver",
    testonly = True,  # Keeps JavaScript somewhat readable
    compile = True,  # Run Closure Compiler
    input_path = "/wit-dashboard/covid19xray_index.html",
    output_path = "/wit-dashboard/covid19xray_demo.html",
    deps = [":covid19xraydemo"],
)

#########################################################################################
tf_web_library(
    name = "ocularncdemo",
    testonly = True,
    srcs = [
        "ocularnc_index.html",
        "wit-ocularnc-demo.html",
        "@org_tf_tfjs//:tf.min.js",
        "@org_tf_tfjs_mobilenet//:mobilenet.js",
    ] + glob(["data/**"]),
    path = "/wit-dashboard",
    deps = [
        "@org_tensorflow_tensorboard//tensorboard/components/tf_imports:polymer",
        "//wit_dashboard",
    ],
)

tensorboard_html_binary(
    name = "ocularncdemoserver",
    testonly = True,  # Keeps JavaScript somewhat readable
    compile = True,  # Run Closure Compiler
    input_path = "/wit-dashboard/ocularnc_index.html",
    output_path = "/wit-dashboard/ocularnc_demo.html",
    deps = [":ocularncdemo"],
)
#########################################################################################


tf_web_library(
    name = "bowelQualitydemo",
    testonly = True,
    srcs = [
        "bowelQuality_index.html",
        "wit-bowelQuality-demo.html",
        "@org_tf_tfjs//:tf.min.js",
        "@org_tf_tfjs_mobilenet//:mobilenet.js",
    ] + glob(["data/**"]),
    path = "/wit-dashboard",
    deps = [
        "@org_tensorflow_tensorboard//tensorboard/components/tf_imports:polymer",
        "//wit_dashboard",
    ],
)

tensorboard_html_binary(
    name = "bowelQualitydemoserver",
    testonly = True,  # Keeps JavaScript somewhat readable
    compile = True,  # Run Closure Compiler
    input_path = "/wit-dashboard/bowelQuality_index.html",
    output_path = "/wit-dashboard/bowelQuality_demo.html",
    deps = [":bowelQualitydemo"],
)

#########################################################################################

tf_web_library(
    name = "malariademo",
    testonly = True,
    srcs = [
        "malaria_index.html",
        "wit-malaria-demo.html",
        "@org_tf_tfjs//:tf.min.js",
        "@org_tf_tfjs_mobilenet//:mobilenet.js",
    ] + glob(["data/**"]),
    path = "/wit-dashboard",
    deps = [
        "@org_tensorflow_tensorboard//tensorboard/components/tf_imports:polymer",
        "//wit_dashboard",
    ],
)

tensorboard_html_binary(
    name = "malariademoserver",
    testonly = True,  # Keeps JavaScript somewhat readable
    compile = True,  # Run Closure Compiler
    input_path = "/wit-dashboard/malaria_index.html",
    output_path = "/wit-dashboard/malaria_demo.html",
    deps = [":malariademo"],
)

#########################################################################################

tf_web_library(
    name = "murademo",
    testonly = True,
    srcs = [
        "mura_index.html",
        "wit-mura-demo.html",
        "@org_tf_tfjs//:tf.min.js",
        "@org_tf_tfjs_mobilenet//:mobilenet.js",
    ] + glob(["data/**"]),
    path = "/wit-dashboard",
    deps = [
        "@org_tensorflow_tensorboard//tensorboard/components/tf_imports:polymer",
        "//wit_dashboard",
    ],
)

tensorboard_html_binary(
    name = "murademoserver",
    testonly = True,  # Keeps JavaScript somewhat readable
    compile = True,  # Run Closure Compiler
    input_path = "/wit-dashboard/mura_index.html",
    output_path = "/wit-dashboard/mura_demo.html",
    deps = [":murademo"],
)

#########################################################################################

tf_web_library(
    name = "irisdemo",
    testonly = True,
    srcs = [
        "iris_index.html",
        "wit-iris-demo.html",
        "@org_tf_tfjs//:tf.min.js",
    ] + glob(["data/**"]),
    path = "/wit-dashboard",
    deps = [
        "@org_tensorflow_tensorboard//tensorboard/components/tf_imports:polymer",
        "//wit_dashboard",
    ],
)

tensorboard_html_binary(
    name = "irisdemoserver",
    testonly = True,  # Keeps JavaScript somewhat readable
    compile = True,  # Run Closure Compiler
    input_path = "/wit-dashboard/iris_index.html",
    output_path = "/wit-dashboard/iris_demo.html",
    deps = [":irisdemo"],
)
############################################################################################################

tf_web_library(
    name = "covid19demo",
    testonly = True,
    srcs = [
        "covid19_index.html",
        "wit-covid19-demo.html",
        "@org_tf_tfjs//:tf.min.js",
    ] + glob(["data/**"]),
    path = "/wit-dashboard",
    deps = [
        "@org_tensorflow_tensorboard//tensorboard/components/tf_imports:polymer",
        "//wit_dashboard",
    ],
)

tensorboard_html_binary(
    name = "covid19demoserver",
    testonly = True,  # Keeps JavaScript somewhat readable
    compile = True,  # Run Closure Compiler
    input_path = "/wit-dashboard/covid19_index.html",
    output_path = "/wit-dashboard/covid19_demo.html",
    deps = [":covid19demo"],
)
############################################################################################################
tf_web_library(
    name = "breastCancerdemo",
    testonly = True,
    srcs = [
        "breastCancer_index.html",
        "wit-breastCancer-demo.html",
        "@org_tf_tfjs//:tf.min.js",
    ] + glob(["data/**"]),
    path = "/wit-dashboard",
    deps = [
        "@org_tensorflow_tensorboard//tensorboard/components/tf_imports:polymer",
        "//wit_dashboard",
    ],
)

tensorboard_html_binary(
    name = "breastCancerdemoserver",
    testonly = True,  # Keeps JavaScript somewhat readable
    compile = True,  # Run Closure Compiler
    input_path = "/wit-dashboard/breastCancer_index.html",
    output_path = "/wit-dashboard/breastCancer_demo.html",
    deps = [":breastCancerdemo"],
)

############################################################################################################
tf_web_library(
    name = "heartdemo",
    testonly = True,
    srcs = [
        "fr_hert_index.html",
        "wit-fr-heart-demo.html",
        "@org_tf_tfjs//:tf.min.js",
    ] + glob(["data/**"]),
    path = "/wit-dashboard",
    deps = [
        "@org_tensorflow_tensorboard//tensorboard/components/tf_imports:polymer",
        "//wit_dashboard",
    ],
)

tensorboard_html_binary(
    name = "heartdemoserver",
    testonly = True,  # Keeps JavaScript somewhat readable
    compile = True,  # Run Closure Compiler
    input_path = "/wit-dashboard/fr_hert_index.html",
    output_path = "/wit-dashboard/heart_demo.html",
    deps = [":heartdemo"],
)

############################################################################################################
tf_web_library(
    name = "depressiondemo",
    testonly = True,
    srcs = [
        "depression_index.html",
        "wit-depression-demo.html",
        "@org_tf_tfjs//:tf.min.js",
    ] + glob(["data/**"]),
    path = "/wit-dashboard",
    deps = [
        "@org_tensorflow_tensorboard//tensorboard/components/tf_imports:polymer",
        "//wit_dashboard",
    ],
)

tensorboard_html_binary(
    name = "depressiondemoserver",
    testonly = True,  # Keeps JavaScript somewhat readable
    compile = True,  # Run Closure Compiler
    input_path = "/wit-dashboard/depression_index.html",
    output_path = "/wit-dashboard/depression_demo.html",
    deps = [":depressiondemo"],
)

############################################################################################################
tf_web_library(
    name = "liverdemo",
    testonly = True,
    srcs = [
        "liver_index.html",
        "wit-liver-demo.html",
        "@org_tf_tfjs//:tf.min.js",
    ] + glob(["data/**"]),
    path = "/wit-dashboard",
    deps = [
        "@org_tensorflow_tensorboard//tensorboard/components/tf_imports:polymer",
        "//wit_dashboard",
    ],
)

tensorboard_html_binary(
    name = "liverdemoserver",
    testonly = True,  # Keeps JavaScript somewhat readable
    compile = True,  # Run Closure Compiler
    input_path = "/wit-dashboard/liver_index.html",
    output_path = "/wit-dashboard/liver_demo.html",
    deps = [":liverdemo"],
)

############################################################################################################
tf_web_library(
    name = "ckddemo",
    testonly = True,
    srcs = [
        "ckd_index.html",
        "wit-ckd-demo.html",
        "@org_tf_tfjs//:tf.min.js",
    ] + glob(["data/**"]),
    path = "/wit-dashboard",
    deps = [
        "@org_tensorflow_tensorboard//tensorboard/components/tf_imports:polymer",
        "//wit_dashboard",
    ],
)

tensorboard_html_binary(
    name = "ckddemoserver",
    testonly = True,  # Keeps JavaScript somewhat readable
    compile = True,  # Run Closure Compiler
    input_path = "/wit-dashboard/ckd_index.html",
    output_path = "/wit-dashboard/ckd_demo.html",
    deps = [":ckddemo"],
)

############################################################################################################

tf_web_library(
    name = "orthopedicdemo",
    testonly = True,
    srcs = [
        "orthopedic_index.html",
        "wit-orthopedic-demo.html",
        "@org_tf_tfjs//:tf.min.js",
    ] + glob(["data/**"]),
    path = "/wit-dashboard",
    deps = [
        "@org_tensorflow_tensorboard//tensorboard/components/tf_imports:polymer",
        "//wit_dashboard",
    ],
)

tensorboard_html_binary(
    name = "orthopedicdemoserver",
    testonly = True,  # Keeps JavaScript somewhat readable
    compile = True,  # Run Closure Compiler
    input_path = "/wit-dashboard/orthopedic_index.html",
    output_path = "/wit-dashboard/orthopedic_demo.html",
    deps = [":orthopedicdemo"],
)


tf_web_library(
    name = "parkinsonsdemo",
    testonly = True,
    srcs = [
        "parkinsons_index.html",
        "wit-parkinsons-demo.html",
        "@org_tf_tfjs//:tf.min.js",
    ] + glob(["data/**"]),
    path = "/wit-dashboard",
    deps = [
        "@org_tensorflow_tensorboard//tensorboard/components/tf_imports:polymer",
        "//wit_dashboard",
    ],
)

tensorboard_html_binary(
    name = "parkinsonsdemoserver",
    testonly = True,  # Keeps JavaScript somewhat readable
    compile = True,  # Run Closure Compiler
    input_path = "/wit-dashboard/parkinsons_index.html",
    output_path = "/wit-dashboard/parkinsons_demo.html",
    deps = [":parkinsonsdemo"],
)



tf_web_library(
    name = "cardemo",
    testonly = True,
    srcs = [
        "car_index.html",
        "wit-car-demo.html",
        "@org_tf_tfjs//:tf.min.js",
    ] + glob(["data/**"]),
    path = "/wit-dashboard",
    deps = [
        "@org_tensorflow_tensorboard//tensorboard/components/tf_imports:polymer",
        "//wit_dashboard",
    ],
)

tensorboard_html_binary(
    name = "cardemoserver",
    testonly = True,  # Keeps JavaScript somewhat readable
    compile = True,  # Run Closure Compiler
    input_path = "/wit-dashboard/car_index.html",
    output_path = "/wit-dashboard/car_demo.html",
    deps = [":cardemo"],
)

tf_web_library(
    name = "agedemo",
    testonly = True,
    srcs = [
        "age_index.html",
        "wit-age-demo.html",
        "@org_tf_tfjs//:tf.min.js",
    ] + glob(["data/**"]),
    path = "/wit-dashboard",
    deps = [
        "@org_tensorflow_tensorboard//tensorboard/components/tf_imports:polymer",
        "//wit_dashboard",
    ],
)

tensorboard_html_binary(
    name = "agedemoserver",
    testonly = True,  # Keeps JavaScript somewhat readable
    compile = True,  # Run Closure Compiler
    input_path = "/wit-dashboard/age_index.html",
    output_path = "/wit-dashboard/age_demo.html",
    deps = [":agedemo"],
)
############################################################################################################
tf_web_library(
    name = "abalonedemo",
    testonly = True,
    srcs = [
        "abalone_index.html",
        "wit-abalone-demo.html",
        "@org_tf_tfjs//:tf.min.js",
    ] + glob(["data/**"]),
    path = "/wit-dashboard",
    deps = [
        "@org_tensorflow_tensorboard//tensorboard/components/tf_imports:polymer",
        "//wit_dashboard",
    ],
)

tensorboard_html_binary(
    name = "abalonedemoserver",
    testonly = True,  # Keeps JavaScript somewhat readable
    compile = True,  # Run Closure Compiler
    input_path = "/wit-dashboard/abalone_index.html",
    output_path = "/wit-dashboard/abalone_demo.html",
    deps = [":abalonedemo"],
)
############################################################################################################
tf_web_library(
    name = "athleteRecoverydemo",
    testonly = True,
    srcs = [
        "athleteRecovery_index.html",
        "wit-athleteRecovery-demo.html",
        "@org_tf_tfjs//:tf.min.js",
    ] + glob(["data/**"]),
    path = "/wit-dashboard",
    deps = [
        "@org_tensorflow_tensorboard//tensorboard/components/tf_imports:polymer",
        "//wit_dashboard",
    ],
)

tensorboard_html_binary(
    name = "athleteRecoverydemoserver",
    testonly = True,  # Keeps JavaScript somewhat readable
    compile = True,  # Run Closure Compiler
    input_path = "/wit-dashboard/athleteRecovery_index.html",
    output_path = "/wit-dashboard/athleteRecovery_demo.html",
    deps = [":athleteRecoverydemo"],
)
############################################################################################################

tf_web_library(
    name = "compasdemo",
    testonly = True,
    srcs = [
        "compas_index.html",
        "wit-compas-demo.html",
        "@org_tf_tfjs//:tf.min.js",
    ] + glob(["data/**"]),
    path = "/wit-dashboard",
    deps = [
        "@org_tensorflow_tensorboard//tensorboard/components/tf_imports:polymer",
        "//wit_dashboard",
    ],
)

tensorboard_html_binary(
    name = "compasdemoserver",
    testonly = True,  # Keeps JavaScript somewhat readable
    compile = True,  # Run Closure Compiler
    input_path = "/wit-dashboard/compas_index.html",
    output_path = "/wit-dashboard/compas_demo.html",
    deps = [":compasdemo"],
)
############################################################################################################
tf_web_library(
    name = "medicalCostdemo",
    testonly = True,
    srcs = [
        "medicalCost_index.html",
        "wit-medicalCost-demo.html",
        "@org_tf_tfjs//:tf.min.js",
    ] + glob(["data/**"]),
    path = "/wit-dashboard",
    deps = [
        "@org_tensorflow_tensorboard//tensorboard/components/tf_imports:polymer",
        "//wit_dashboard",
    ],
)

tensorboard_html_binary(
    name = "medicalCostdemoserver",
    testonly = True,  # Keeps JavaScript somewhat readable
    compile = True,  # Run Closure Compiler
    input_path = "/wit-dashboard/medicalCost_index.html",
    output_path = "/wit-dashboard/medicalCost_demo.html",
    deps = [":medicalCostdemo"],
)
############################################################################################################
tf_web_library(
    name = "mortalityPredictiondemo",
    testonly = True,
    srcs = [
        "mortalityPrediction_index.html",
        "wit-mortalityPrediction-demo.html",
        "@org_tf_tfjs//:tf.min.js",
    ] + glob(["data/**"]),
    path = "/wit-dashboard",
    deps = [
        "@org_tensorflow_tensorboard//tensorboard/components/tf_imports:polymer",
        "//wit_dashboard",
    ],
)

tensorboard_html_binary(
    name = "mortalityPredictiondemoserver",
    testonly = True,  # Keeps JavaScript somewhat readable
    compile = True,  # Run Closure Compiler
    input_path = "/wit-dashboard/mortalityPrediction_index.html",
    output_path = "/wit-dashboard/mortalityPrediction_demo.html",
    deps = [":mortalityPredictiondemo"],
)
############################################################################################################
