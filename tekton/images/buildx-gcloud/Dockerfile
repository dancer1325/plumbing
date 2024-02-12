# Copyright 2020 The Tekton Authors
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
FROM gcr.io/google.com/cloudsdktool/cloud-sdk:alpine@sha256:ae59354428a800389be25c061e6d9e6b3ebd18278c3f9edb5b9f9f3bb66ef628
LABEL maintainer "Tekton Authors <tekton-dev@googlegroups.com>"

RUN  mkdir -p ~/.docker/cli-plugins \
     && curl -fsSL https://github.com/docker/buildx/releases/download/v0.8.1/buildx-v0.8.1.linux-amd64 > ~/.docker/cli-plugins/docker-buildx \
     && chmod u+x ~/.docker/cli-plugins/docker-buildx
