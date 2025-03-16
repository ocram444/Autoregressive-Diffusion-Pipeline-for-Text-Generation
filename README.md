<div align="center">
	<img width="350" height="350" src="images/Logo.webp" alt="Project_Logo">
	<br>
	<br>
	<div>
		<h2>
			<a href="#">Autoregressive-Diffusion-Pipeline-for-Text-Generation</a>
			<br><br>
			<sup>Dual pipeline for improved text generation alignment</sup>
		</h2>
	</div>
</div>  

[![Widget0](https://img.shields.io/badge/contributers-just_me-blue)](#)
[![Widget1](https://img.shields.io/badge/lead_developer-me-blue)](#)
[![Widget3](https://img.shields.io/badge/version-0.1-blue)](#)
[![Widget4](https://img.shields.io/badge/project_status-Active-blue)](#)
[![Widget5](https://img.shields.io/badge/last_update-March_2025-blue)](#)
[![Widget6](https://img.shields.io/badge/languages_used-Python-green)](#)
[![Widget7](https://img.shields.io/badge/lines_of_code-TBA-green)](#)
[![Widget8](https://img.shields.io/badge/build_size-0_kb-green)](#)
[![Widget8](https://img.shields.io/badge/GitHub_Stars-⭐_1-gray)](#)

<div align="center">	
	<hr>
	<p>
		<p>
			<sup>
				<a href="#">No link to arXiv paper yet 📖</a>
			</sup>
		</p>
		<sup>Special thanks to:</sup>
		<br>
		<br>
		<a href="https://www.uni-wuppertal.de/de/">
			<b>Bergische Universität Wuppertal</b>
			<div>
				<sub>Bergische Universität Wuppertal provided valuable learning resources and guidance on the projects direction.</sub>
			</div>
		</a>
    
	
</div>
<br>
<br>
<hr>
<br>
<p align="center">
	<a href="#abstract">Abstract</a>&nbsp;&nbsp;&nbsp;
	<a href="#approach">Approach</a>&nbsp;&nbsp;&nbsp;
	<a href="#code">Code</a>&nbsp;&nbsp;&nbsp;
	<a href="#results">Results</a>&nbsp;&nbsp;&nbsp;
	<a href="#future-works">Future Works</a>&nbsp;&nbsp;&nbsp;
	<a href="#credits">Credits</a>&nbsp;&nbsp;&nbsp;
</p>
<br>
<br>
<p align="center">
	Autoregressive & Diffusion LM is a hybrid framework that combines autoregressive language models (ARLMs) with diffusion-based language models (DLMs) for improved text alignment and refinement. By leveraging ARLMs for initial generation and DLMs for iterative correction, Pipeline enables more controlled, accurate, and adaptable text generation.
</p>
<br>
<br>
<br>

## Abstract
<a id="abstract"></a>

Autoregressive language models (ARLMs) have achieved remarkable progress in text generation, but they still often struggle with controllability and alignment. Recent work on diffusion-based models for language modeling has introduced new possibilities for iterative refinement and text editing. In this work, we propose a hybrid framework that integrates ARLMs with diffusion-based models to improve alignment and coherence. By leveraging diffusion’s ability to iteratively refine text, our approach enables post-hoc correction and controlled editing of autoregressively generated content using auxiliary prompts. We present the architecture, training strategies, and experimental results demonstrating improved alignment and adaptability in text generation.

## Approach
<a id="approach"></a>

Our proposed Pipeline framework integrates autoregressive language models (ARLMs) with diffusion-based language models (DLMs) to enhance text generation through iterative refinement. This hybrid approach leverages the strengths of both paradigms: ARLMs excel in fluent, high-quality text generation, while DLMs offer a powerful mechanism for controlled editing and correction.

At a high level, Pipeline operates in two stages:

- Autoregressive Generation: An ARLM produces an initial text output based on a given prompt. This stage ensures efficiency and fluency in generating coherent sequences.
- Diffusion-based Refinement: A diffusion language model takes the ARLM-generated text and iteratively refines it using a secondary conditioning prompt. This allows for correction, alignment, and enhanced controllability while preserving fluency.
To achieve seamless integration, we explore latent-space diffusion, where text representations are iteratively denoised rather than modifying raw tokens directly. This enables smooth, targeted refinements while maintaining contextual consistency. Additionally, we introduce alignment-aware conditioning, where the diffusion model receives both the original prompt and a secondary guidance prompt to enforce desired modifications without excessive drift from the ARLM’s intent.

Our approach balances generation speed, coherence, and flexibility, making it well-suited for applications requiring controllable text generation, post-generation alignment, and iterative text editing. We demonstrate the effectiveness of Pipeline across tasks such as content refinement, bias mitigation, and controlled rewriting, hopefully showing significant improvements over standalone ARLMs.


## Code
<a id="code"></a>

To Be Published

  
## Results
<a id="results"></a>

To Be Determined


## Future works
<a id="future-works"></a>

## Credits
<a id="credits"></a>
