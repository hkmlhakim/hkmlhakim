"completed_at": "2024-03-05T13:46:13.813133Z",
  "created_at": "2024-03-05T13:45:50.761895Z",
  "error": null,
  "id": "pft2dadbcdnh25z5ktctsj3sze",
  "input": {
    "image": "https://replicate.delivery/pbxt/KW7Getr2zD5ECxySdBZtLmPa322lNkXrpkMdKcmxeaDmq2b1/MTk4MTczMTkzNzI1Mjg5NjYy.webp",
    "style": "pixel",
    "prompt": "a person in a game grand thief auto",
    "negative_prompt": "",
    "prompt_strength": 4.5,
    "denoising_strength": 0.65,
    "instant_id_strength": 0.8
  },
  "logs": "Random seed set to: 3672888193\nChecking inputs\n✅ /tmp/inputs/input.webp\n====================================\nRunning workflow\ngot prompt\nExecuting node 3, title: LoRA Stacker, class type: LoRA Stacker\nExecuting node 2, title: Efficient Loader, class type: Efficient Loader\nRequested to load SDXLClipModel\nLoading 1 new model\n----------------------------------------\n\u001b[36mEfficient Loader Models Cache:\u001b[0m\nCkpt:\n[1] albedobaseXL_v13\nLora:\n[1] base_ckpt: albedobaseXL_v13\nlora(mod,clip): ClayAnimationRedm(1,1)\nExecuting node 41, title: Apply InstantID, class type: ApplyInstantID\nExecuting node 51, title: VAE Encode, class type: VAEEncode\nExecuting node 4, title: KSampler (Efficient), class type: KSampler (Efficient)\nRequested to load SDXL\nRequested to load ControlNet\nRequested to load ControlNet\nLoading 3 new models\n  0%|          | 0/20 [00:00<?, ?it/s]\n  5%|▌         | 1/20 [00:00<00:05,  3.26it/s]\n 10%|█         | 2/20 [00:00<00:05,  3.26it/s]\n 15%|█▌        | 3/20 [00:00<00:05,  3.28it/s]\n 20%|██        | 4/20 [00:01<00:04,  3.28it/s]\n 25%|██▌       | 5/20 [00:01<00:04,  3.28it/s]\n 30%|███       | 6/20 [00:01<00:04,  3.29it/s]\n 35%|███▌      | 7/20 [00:02<00:03,  3.27it/s]\n 40%|████      | 8/20 [00:02<00:03,  3.27it/s]\n 45%|████▌     | 9/20 [00:02<00:03,  3.29it/s]\n 50%|█████     | 10/20 [00:03<00:03,  3.29it/s]\n 55%|█████▌    | 11/20 [00:03<00:02,  3.29it/s]\n 60%|██████    | 12/20 [00:03<00:02,  3.30it/s]\n 65%|██████▌   | 13/20 [00:03<00:02,  3.30it/s]\n 70%|███████   | 14/20 [00:04<00:01,  3.30it/s]\n 75%|███████▌  | 15/20 [00:04<00:01,  3.30it/s]\n 80%|████████  | 16/20 [00:04<00:01,  3.32it/s]\n 85%|████████▌ | 17/20 [00:05<00:00,  3.32it/s]\n 90%|█████████ | 18/20 [00:05<00:00,  3.33it/s]\n 95%|█████████▌| 19/20 [00:05<00:00,  3.37it/s]\n100%|██████████| 20/20 [00:06<00:00,  3.41it/s]\n100%|██████████| 20/20 [00:06<00:00,  3.31it/s]\nExecuting node 5, title: Save Image, class type: SaveImage\nPrompt executed in 20.70 seconds\noutputs:  {'4': {'images': []}, '5': {'images': [{'filename': 'ComfyUI_00001_.png', 'subfolder': '', 'type': 'output'}]}}\n====================================\nContents of /tmp/outputs:\nComfyUI_00001_.png",
  "metrics": {
    "predict_time": 23.016322,
    "total_time": 23.051238
  },
  "output": [
    "![20230410025759_IMG_6366](https://github.com/hkmlhakim/hkmlhakim/assets/164167010/0d678383-7dd3-4c14-91af-5d0659da1a27)
"
  ],
  "started_at": "2024-03-05T13:45:50.796811Z",
  "status": "succeeded",
  "urls": {
    "get": "https://api.replicate.com/v1/predictions/pft2dadbcdnh25z5ktctsj3sze",
    "cancel": "https://api.replicate.com/v1/predictions/pft2dadbcdnh25z5ktctsj3sze/cancel"
  },
  "version": "edc6439ac55af138defbca7c472b38bcdd62c61797e8e0c2fae88696cd8afb25"
}
