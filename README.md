<div align="center">
  <img src="https://github.com/vdutts7/dump/blob/main/stanchat-logo.png" alt="Logo" width="80" height="80">
    <h1 align="center">
        Stanchat
    </h1>
    <p align="center"> 
        <i><b>AI Character Chats 🧞‍♂️</b></i>
        <br /> 
    </p>

[![Website][website]][website-url]
[![Github][github]][github-url]

 </div>

<br/>

## Table of Contents

<ol>
    <a href="#about">📝 About</a>
        <ul>
        </ul>
    <a href="#how-to-build">💻 How to build</a>
    <a href="#next-steps">🚀 Next steps</a> 
       <ul>
        </ul>
    <a href="#tools-used">🔧 Tools used</a>
        <ul>
        </ul>
    <a href="#contact">👤 Contact</a>
  </ol>

<br/>

## 📝About
- User web app that simulates conversations with celebrity personas.
- Beautiful modern chat interface.
- Includes User Auth.
- Examples in demo:
  1. Kanye West
  2. Ariana Grande
  3. Jake Paul

<br/>

## 💻How to Build
- Fine-tuned OpenAI's `davinci-003` model (via `GPT-3 API`) and pyTorch
- Basic RLHF using:
  - outside training datasets sourced from YouTube, Wikipedia, old Tweets
  - vectorized embeddings of interview transcripts and long format dialogue from videos, speeches, publications
  - Processed layers weights via Weights & Biases
  - Prompt engineered inputs for engaging + realistic conversation based on actual celebrity's style of speaking
- Backend via FastAPI
- User authentication via Firebase
- React frontend with TailwindCSS styling

<br/>

## 🚀Next Steps

- Add WAY more characters
- Automating RLHF process
- Long-term memory storage
  - Extending LLM context windows,likely using [chromaDB](https://www.trychroma.com/)
- Multimodal chat
  - Enable TTS, likely using [ElevenLabs](https://elevenlabs.io/)
  - Potentially video chat incorporating GANs, Wav2Lip, and STIT
- More LLMs to choose from
  - GPT-4
  - LLaMa 2
  - Anthropic
  - Falcon-LLM

<br/>

## 🔧Tools Used

[![OpenAI][openai]][openai-url]
[![pyTorch][pytorch]][pytorch-url]
[![Wandb][wandb]][wandb-url]
[![FastAPI][FastAPI]][FastAPI-url]
[![PostgreSQL][postgresql]][postgresql-url]
[![Firebase][firebase]][firebase-url]
[![React][react]][react-url]
[![TailwindCSS][tailwindcss]][tailwindcss-url]
[![Vercel][Vercel]][Vercel-url]


<br/>

## 👤Contact

[![Email][email]][email-url]
[![Twitter][twitter]][twitter-url]

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[react]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[react-url]: https://reactjs.org/
[tailwindcss]: https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=skyblue&color=0A192F
[tailwindcss-url]: https://tailwindcss.com/
[pytorch]: https://img.shields.io/badge/pyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white
[pytorch-url]: https://pytorch.org/
[FastAPI]: https://img.shields.io/badge/FastAPI-009485?style=for-the-badge&logo=fastapi&logoColor=white
[FastAPI-url]: https://fastapi.tiangolo.com/
[openai]: https://img.shields.io/badge/OpenAI_GPT--3.5-0058A0?style=for-the-badge&logo=openai&logoColor=white&color=4aa481
[openai-url]: https://openai.com/
[firebase]: https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=yellow&color=blue
[firebase-url]: https://firebase.google.com/
[wandb]: https://img.shields.io/badge/Weights_&_Biases-FFBE00?style=for-the-badge&logo=weightsandbiases&logoColor=black
[wandb-url]: https://wandb.ai/site
[postgresql]: https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white
[postgresql-url]: https://www.postgresql.org/
[vercel]: https://img.shields.io/badge/Vercel-FFFFFF?style=for-the-badge&logo=Vercel&logoColor=white&color=black
[vercel-url]: https://Vercel.com/
[website]: https://img.shields.io/badge/🔗Website-7f18ff?style=for-the-badge
[website-url]: https://stan.chat
[github]: https://img.shields.io/badge/💻Github-000000?style=for-the-badge
[github-url]: https://github.com/vdutts7/stanchat/
[email]: https://img.shields.io/badge/me@vdutts7.com-FFCA28?style=for-the-badge&logo=Gmail&logoColor=00bbff&color=black
[email-url]: #
[twitter]: https://img.shields.io/badge/Twitter-FFCA28?style=for-the-badge&logo=Twitter&logoColor=00bbff&color=black
[twitter-url]: https://twitter.com/vdutts7/
