#Creating build file

py_binary(
    name = "hello",
    srcs = ["first.py"],
    main = "first.py",
    )

py_test(
    name = "first_test",
    srcs = ["first_test.py",],
    deps = [":hello"],
    )
