#
# Copyright 2022 Toyota Connected North America
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#      http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
#

set(OPT_BACKEND_GLFW OFF)
set(OPT_BACKEND_BARE_GLES3 ON)
set(OPT_BUILD_RTL_SDR_SOURCE ON)
set(OPT_BUILD_SDRPLAY_SOURCE ON)
add_subdirectory(SDRPlusPlus)
