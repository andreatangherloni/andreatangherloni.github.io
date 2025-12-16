---
title: "Now You See Me, Now You Don't: A Unified Framework for Expression Consistent Anonymization in Talking Head Videos"
collection: publications
category: conferences
permalink: /publication/ICCV-NowYouSeeMe
excerpt: 'To enable privacy-preserving video analysis, we propose AnonNET, a diffusion-based system that de-identifies faces yet maintains age, gender, pose, expression, and realistic temporal dynamics.'
date: 2025-10-19
venue: 'IEEE/CVF International Conference on Computer Vision (ICCV)'
paperurl: 'https://openaccess.thecvf.com/content/ICCV2025W/CV4BIOM/html/Egin_Now_You_See_Me_Now_You_Dont_A_Unified_Framework_ICCVW_2025_paper.html'
citation: 'Egin A., Tangherloni A., Dantcheva A. (2025). Now You See Me, Now You Don't: A Unified Framework for Expression Consistent Anonymization in Talking Head Videos. In IEEE/CVF International Conference on Computer Vision (ICCV), IEEE.'
---

Face video anonymization is aimed at privacy preservation while allowing for the analysis of videos in a number of computer vision downstream tasks such as expression recognition, people tracking, and action recognition. We propose here a novel unified framework referred to as AnonNET, streamlined to de-identify a facial video, while preserving age, gender, race, pose, and expression of the original video. Specifically, we inpaint faces by a diffusion-based generative model guided by high-level attribute recognition and motion-aware expression transfer. We then animate de-identified faces by video-driven animation, which accepts the de-identified face and the original video as input. Extensive experiments on the datasets VoxCeleb2, CelebV-HQ, and HDTF, which include diverse facial dynamics, demonstrate the effectiveness of AnonNET in obfuscating identity while retaining visual realism and temporal consistency.