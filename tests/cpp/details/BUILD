# Copyright 2022 Ketan Goyal
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

cc_test(
    name = "random_test",
    srcs = [
        "random_test.cpp",
    ],
    deps = [
        "//cpp:inspector",
        "@gtest//:gtest_main",
    ],
)

cc_test(
    name = "circular_queue_test",
    srcs = [
        "circular_queue_test.cpp",
    ],
    args = ["--gtest_repeat=100"],
    deps = [
        "//cpp:inspector",
        "//utils:chrono",
        "//utils:threads",
        "@gtest//:gtest_main",
    ],
)

cc_test(
    name = "shared_object_test",
    srcs = [
        "shared_object_test.cpp",
    ],
    deps = [
        "//cpp:inspector",
        "//utils:chrono",
        "//utils:threads",
        "@gtest//:gtest_main",
    ],
)
