# Open Genjitsu 4.0

A free, single-page mobile web app (iPhone Safari / Android Chrome):

1. **Driving video**: pick an MP4 from your phone, or paste an `.m3u8` HLS link and stitch it into an MP4 in the browser (mux.js).
2. **Character photo(s)**: one photo, or two for a second pass.
3. **Swap**: runs [Wan 2.2 Animate](https://huggingface.co/spaces/alexnasa/Wan2.2-Animate-ZEROGPU) on Hugging Face's free ZeroGPU through `@gradio/client`.

Your Hugging Face token is entered in ⚙️ Settings and stays in your browser's local storage. It is never stored in this repository.

Free ZeroGPU time is limited to a few GPU-minutes per account per day, so keep clips short and use Low Res.
