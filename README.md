# 📸 Wanghong Aesthetic FLUX.1 (Full Fine-tune)
# FLUX.1 网红氛围感全量微调大模型

<img src="https://applesay-meye.oss-cn-shanghai.aliyuncs.com/meye/1fb72b5a40bd2de6c9c2de3354a8adc8e2a063221f15925e1a776ac0dd9f8ed0.png" width="30%"> <img src="https://applesay-meye.oss-cn-shanghai.aliyuncs.com/meye/1cf624f837501296d14038d06769b140b85efdefdb97951d2830b5f0943dbb82.png" width="30%"> <img src="https://applesay-meye.oss-cn-shanghai.aliyuncs.com/meye/bc7a13a6f2936aa32404cea8ef31b5c403018ca65301ebe51d15f17314ddcf8f.png" width="30%">

✨ Introduction / 简介
Welcome to the Wanghong Aesthetic Model.
欢迎使用网红氛围感大模型。

**Model Download / 模型下载:**
[https://huggingface.co/Applesay123456/REDland_Aesthetic_FLUX.1_v1/tree/main](https://huggingface.co/Applesay123456/REDland_Aesthetic_FLUX.1_v1/tree/main)、

[https://www.modelscope.cn/models/applesay123456/REDland_Aesthetic_FLUX.1_v1](https://www.modelscope.cn/models/applesay123456/REDland_Aesthetic_FLUX.1_v1)

Unlike common LoRAs, this is a Full Fine-tune (Checkpoint) based on the FLUX.1 architecture. We have retrained the model weights to natively understand the nuances of Asian lifestyle photography, lighting, and fashion.

不同于常见的 LoRA，这是一个基于 FLUX.1 架构的全量微调大模型 (Checkpoint)。我们对模型权重进行了重新训练，使其能从底层原生理解亚洲生活方式摄影、光影和时尚的细微差别。

🚀 Why Full Fine-tune? / 为什么要用全量微调版？
No LoRA Needed: Just load the checkpoint and generate. No complex node setups. (无需挂载 LoRA，加载模型即可直接生成)

Better Consistency: The style is "baked" into the model, offering superior consistency and prompt adherence compared to adapters. (风格已融入模型底层，比外挂 LoRA 具有更好的一致性和提示词跟随性)

High Fidelity: Optimized for photorealism, "glass skin" texture, and "phone-camera" aesthetics. (针对照片真实感、水光肌质感和手机直出感进行了深度优化)

🔧 Model Details / 模型信息
Architecture: FLUX.1 (Fine-tuned)
Type: Checkpoint / Diffusion Model (Not a LoRA)
Trigger Word: XHS (Optional but recommended / 可选，但推荐加上以增强风格)
File Format: .safetensors (Cleaned & Safe / 已清洗元数据，安全无毒)
🎨 Prompt Showcase / 提示词示例
This model is built on FLUX, so it prefers Natural Language Prompts (Descriptive sentences).
本模型基于 FLUX，因此更喜欢自然语言提示词（描述性长句）。
1. Sweet Campus Style / 清纯校园感 🏫

XHS, A high-resolution photograph of a beautiful young girl with a sweet smile, standing on a sunny university campus. She has long straight black hair with bangs and is wearing a crisp white shirt with a plaid skirt (JK uniform). The lighting is natural and soft, with sunlight filtering through the trees creating a dreamy lens flare. The image has a Fujifilm film aesthetic, capturing a pure and innocent first-love vibe with a soft blurred background.
![Sweet Campus Style](https://applesay-meye.oss-cn-shanghai.aliyuncs.com/meye/293bb50ebdc6f851bb767e58047229b6d4ce54d3e329c6423665ef6574818788.png)
**Sampler / 采样器:** deis | **Scheduler / 调度器:** ddim_uniform | **Steps / 步数:** 26

2. French Lazy Afternoon / 法式慵懒下午茶 ☕

XHS, A candid lifestyle shot of an elegant girl sitting by the window in a cozy coffee shop. She is wearing a beige oversized sweater and a beret, exuding a relaxed French style. She is holding a ceramic coffee cup and looking out the window, not at the camera. The afternoon sun casts a warm, cinematic glow on her face. The image has high detailed skin texture and a depth of field that focuses on her, conveying a lazy and sophisticated afternoon tea atmosphere.
![French Lazy Afternoon](https://github.com/applesay20160204/REDland_Aesthetic_FLUX.1_v1/blob/main/1121-2.png)
**Sampler / 采样器:** deis | **Scheduler / 调度器:** ddim_uniform | **Steps / 步数:** 26

3. Urban Street Fashion / 高街酷飒 OOTD 🕶️

XHS, A dynamic full-body street fashion photo of a confident girl walking down a busy city street at sunset. She is wearing a trendy crop top, loose denim jeans, and has headphones resting around her neck. The wind is gently blowing her hair. She has a cool expression and is looking straight ahead. The background features a blurred city crowd and golden hour lighting. The style is high-contrast urban photography, shot on an 85mm lens with sharp focus on the subject.
![Urban Street Fashion](https://applesay-meye.oss-cn-shanghai.aliyuncs.com/meye/a23b96d231bdf7bba6ab7f2c0c130520061a0ac06fedcc4d74065b5e77750d8b.png)
**Sampler / 采样器:** deis | **Scheduler / 调度器:** ddim_uniform | **Steps / 步数:** 26

4. Cozy Home "No-Makeup" Look / 伪素颜居家感 🏠

XHS, A realistic mirror selfie taken by a cute girl in her bedroom. She is sitting on the bed with a messy bun hairstyle, wearing comfortable grey pajamas and an oversized hoodie. She has a "no makeup" makeup look with clear, glass skin. The room is slightly messy but cozy, illuminated by soft morning light coming from the window. The photo has a casual, intimate social media vibe, capturing a relaxed moment at home.
![Cozy Home No-Makeup Look](https://applesay-meye.oss-cn-shanghai.aliyuncs.com/meye/401541af0e8f2952e6089f0f814a4ddb23cc832dad655ed13db730a115226afc.png)
**Sampler / 采样器:** deis | **Scheduler / 调度器:** ddim_uniform | **Steps / 步数:** 26

5. Hong Kong Retro Night / 港风复古夜景 🌃

XHS, A cinematic night portrait with a vintage Hong Kong film aesthetic. A girl with wavy hair and red lipstick is standing on a street filled with neon signs. She is wearing a black dress and has a melancholic, emotional expression. The lighting is moody with blue and red neon reflections on her face. The image has a film grain texture, slight chromatic aberration, and a soft diffusion effect, resembling a scene from a Wong Kar-wai movie.
![Hong Kong Retro Night](https://github.com/applesay20160204/REDland_Aesthetic_FLUX.1_v1/blob/main/1121-5.png)
**Sampler / 采样器:** deis | **Scheduler / 调度器:** ddim_uniform | **Steps / 步数:** 26

选择发布的版本是75轮生成的，效果最佳
选择发布的版本是75轮生成的，效果最佳

⚙️ Usage / 使用方法
ComfyUI
Place the file in: ComfyUI/models/diffusion_models/ (NOT models/loras/)
将文件放入 diffusion_models 文件夹，而不是 loras 文件夹

Use the UNet Loader node.
使用 UNet Loader 节点加载

Recommended Sampler: deis

Recommended Scheduler: ddim_uniform

Recommended Steps: 20-30

CFG:1

📄 License / 许可
Based on FLUX.1. Please refer to the original FLUX.1 license for commercial usage restrictions (if applicable).
本模型基于 FLUX.1 微调。商业使用限制请参考原始 FLUX.1 许可协议。
