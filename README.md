<img width="1500" height="1000" alt="image" src="https://github.com/user-attachments/assets/93c024df-c619-4212-b773-7418c75c3ca8" />
<li>
  <ol>Labelled Dataset: https://huggingface.co/datasets/mohammedfaisalkhan4000/RoomMind-Interior-Labels</ol>
  <ol>This dataset represents the 'Gold Standard' labels used to fine-tune the SmolVLM-250M student model. By distilling the knowledge of a 3B parameter Vision-Language Model into a 250M parameter architecture, the SmolVLM-250M was able to achieve structured JSON extraction capabilities in a footprint small enough for edge and mobile deployment."</ol>
  <br>
  <ol>Fine-tuned model: https://huggingface.co/mohammedfaisalkhan4000/RoomMind-SmolVLM2-500M</ol>
  <ol>Fine-tuned SmolVLM2-500M-Instruct on 1,000 AI-labelled interior room images using LoRA + SFT to extract structured furniture JSON (name, style, price) for offline mobile inference.</ol>
</li>
