# CapERA: Captioning Events in Aerial Videos


## Overview
This repository contains the CapERA dataset for events captioning in aerial videos described in this paper: <a href="https://www.mdpi.com/2072-4292/15/8/2139"> "CapERA: Captioning Events in Aerial Videos"</a> by Laila Bashmal, Yakoub Bazi, Mohamad Mahmoud Al Rahhal, Mansour Zuair, and Farid Melgani.



![CapERA](CapERA_figure.gif)

## Abstract
In this paper, we introduce the CapERA dataset, which upgrades the  <a href="https://lcmou.github.io/ERA_Dataset">Event Recognition in Aerial Videos (ERA) dataset</a> to aerial video captioning. The newly proposed dataset aims to advance visual–language-understanding tasks for UAV videos by providing each video with diverse textual descriptions. To build the dataset, 2864 aerial videos are manually annotated with a caption that includes information such as the main event, object, place, action, numbers, and time. More captions are automatically generated from the manual annotation to take into account as much as possible the variation in describing the same video. Furthermore, we propose a captioning model for the CapERA dataset to provide benchmark results for UAV video captioning. The proposed model is based on the encoder–decoder paradigm with two configurations to encode the video. The first configuration encodes the video frames independently by an image encoder. Then, a temporal attention module is added on the top to consider the temporal dynamics between features derived from the video frames. In the second configuration, we directly encode the input video using a video encoder that employs factorized space–time attention to capture the dependencies within and between the frames. For generating captions, a language decoder is utilized to autoregressively produce the captions from the visual tokens. The experimental results under different evaluation criteria show the challenges of generating captions from aerial videos. We expect that the introduction of CapERA will open interesting new research avenues for integrating natural language processing (NLP) with UAV video understandings.

