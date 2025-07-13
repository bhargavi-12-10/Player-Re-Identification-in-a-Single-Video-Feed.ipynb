# Player-Re-Identification-in-a-Single-Video-Feed.ipynb
# Player Re-Identification in Sports Footage 🎯

## 📌 Project Overview

This project solves the problem of tracking football players in a 15-second video using a single-camera feed. Players are detected using YOLOv11 and consistently tracked with StrongSORT, even when they leave and re-enter the frame.

## 📂 Files

- `15sec_input_720p.mp4` – Input video (provided)
- `yolov11_custom.pt` – Fine-tuned detection model
- `track_players.ipynb` – Notebook for detection + tracking
- `tracked_output.avi` – Final output with player IDs
- `Player_ReID_Report.pdf` – Full documentation (15+ pages)

## 🚀 How to Run

1. Clone or download the repository.
2. Open `track_players.ipynb` in Google Colab or Jupyter Notebook.
3. Upload:
   - Your input video
   - The YOLOv11 model (`yolov11_custom.pt`)
4. Run the notebook to generate output video.
5. Check `tracked_output.avi` for results.

## 🧠 Tools Used

- Python
- YOLOv11 (Ultralytics)
- OpenCV
- Deep SORT / StrongSORT
- Google Colab

## 📄 Report

A detailed report outlining the methodology, code flow, results, and future improvements is included in `/report/Player_ReID_Report.pdf`.

## 🙌 Acknowledgments

Thanks to Liat AI for the opportunity to work on this real-world challenge!
