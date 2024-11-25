Copyright 2024 Google, LLC. This software is provided as-is,
without warranty or representation for any use or purpose. Your
use of it is subject to your agreement with Google.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

# Categorization and Complex System Instructions

This notebook provides an example for simplifying long or complex system instructions when using Gemini on Vertex AI. Complex instructions can increase the chance of the model misinterpreting parts of the prompt and deviating from the intended behavior. A general best practice when interacting with most LLMs is to favor clarity, modularity, and explicitness with your instructions. In this example we will see how we can use a categorization agent to help determine the appropraite system instruction. 

For more information please visit https://cloud.google.com/vertex-ai/generative-ai/docs/multimodal/send-chat-prompts-gemini and https://cloud.google.com/vertex-ai/generative-ai/docs/learn/prompts/system-instructions