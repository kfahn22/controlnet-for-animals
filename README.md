# Controlnet For Animals

looking into control net for animals

## DeepLabCut

[DeepLabCut](https://github.com/DeepLabCut/DeepLabCut-live)

[Installation](https://github.com/DeepLabCut/DeepLabCut-live/blob/master/docs/install_desktop.md)

[Real-time, low-latency closed-loop feedback using markerless posture tracking](https://elifesciences.org/articles/61909)


## OpenPifPaf
[OpenPifPaf](https://openpifpaf.github.io/plugins_animalpose.html)

[Coco-person-keypoints](https://openpifpaf.github.io/datasets.html#coco-person-keypoints)

[Animal keypoints](https://openpifpaf.github.io/plugins_animalpose.html)

Add this checkpoint to the prediction command

`--checkpoint shufflenetv2k30-animalpose`

`%%bash`
`python -m openpifpaf.predict images/tappo_loomo.jpg --image-output \`
    `--checkpoint=shufflenetv2k30-animalpose \`
    `--line-width=6 --font-size=6 --white-overlay=0.3 --long-edge=500`


[Animal Pose dataset](https://sites.google.com/view/animal-pose/)



[Shufflenet v2](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwiUveSb6qb-AhVWlGoFHZd4C60QtwJ6BAgeEAI&url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3D3vf3rYf0lTU&usg=AOvVaw0fvZEZcIJJIKXWxxWs_tZB)