<div align="center">
	<img width="500" height="350" src="media/logo.png" alt="Project_Logo">
	<br>
	<br>
	<div>
		<h2>
			<a href="https://link">Autoregressive-Diffusion-Pipeline-for-Text-Generation</a>
			<br><br>
			<sup>Dual pipeline for improved text generation alignment</sup>
		</h2>
	</div>
</div>  

[![Widget0](https://img.shields.io/badge/contributers-Just_me-blue)](link)
[![Widget1](https://img.shields.io/badge/lead_developer-Me-blue)](link)
[![Widget2](https://img.shields.io/badge/mentor-Myself-blue)](link)
[![Widget3](https://img.shields.io/badge/version-0.1-blue)](link)
[![Widget4](https://img.shields.io/badge/project_status-Active-blue)](link)
[![Widget5](https://img.shields.io/badge/last_update-March_2025-blue)](link)
[![Widget6](https://img.shields.io/badge/languages_used-Python-green)](link)
[![Widget7](https://img.shields.io/badge/lines_of_code-0-green)](link)
[![Widget8](https://img.shields.io/badge/build_size-0_kb-green)](link)
[![Widget8](https://img.shields.io/badge/GitHub_Stars-⭐_0-gray)](link)

<div align="center">	
	<hr>
	<p>
		<p>
			<sup>
				<a href="https://link">No link to arXiv paper yet 📖</a>
			</sup>
		</p>
		<sup>Special thanks to:</sup>
		<br>
		<br>
		<a href="link acm ai lab">
			<div>
				<img width="200" src="media/ACM_AI_Lab_Logo_Black.png" alt="ACM AI Lab - Logo">
    			</div>
			<b>ACM AI Lab</b>
			<div>
				<sub>Research Project Conducted as part of the ACM AI Lab</sub><br>
				<sub>Uncertainty quantification in deep learning</sub>
			</div>
		</a>
		<br>
		<br>
		<br>
		<a href="https://link uni wuppertal">
			<div>
				<img src="media/BUW_Logo.jpg" width="250" alt="Bergische Universität Wuppertal - Logo">
			</div>
			<b>Bergische Universität Wuppertal</b>
			<div>
				<sub>In colaboration with Bergische Universität Wuppertal as part of School of Mathematics and Natural Sciences</sub>
			</div>
		</a>
    <br>
		<br>
		<br>
		<a href="link weitere partner">
			<div>
				<img src="media/missing.png" width="100" alt="weitere partner - Logo">
			</div>
			<b>Other partners</b>
			<div>
				<sub>Explaining the colaboration with other partnets </sub>
			</div>
		</a>
		<br>
		<br>
	</p>
	<hr>
	<br>
	<br>
	<br>
	<br>
</div>
<p align="center">
	<a href="link">Abstract</a>&nbsp;&nbsp;&nbsp;
	<a href="link">Approach</a>&nbsp;&nbsp;&nbsp;
	<a href="link">Code</a>&nbsp;&nbsp;&nbsp;
	<a href="link">Results</a>&nbsp;&nbsp;&nbsp;
	<a href="link">arxiv</a>&nbsp;&nbsp;&nbsp;
</p>
<br>
<br>
<p align="center">
	short project description.
</p>
<br>
<br>
<br>

## Abstract

Autoregressive language models (ARLMs) have achieved remarkable progress in text generation, but they still often struggle with controllability and alignment. Recent work on diffusion-based models for language modeling has introduced new possibilities for iterative refinement and text editing. In this work, we propose a hybrid framework that integrates ARLMs with diffusion-based models to improve alignment and coherence. By leveraging diffusion’s ability to iteratively refine text, our approach enables post-hoc correction and controlled editing of autoregressively generated content using auxiliary prompts. We present the architecture, training strategies, and experimental results demonstrating improved alignment and adaptability in text generation.

## Approach

Our proposed Pipeline framework integrates autoregressive language models (ARLMs) with diffusion-based language models (DLMs) to enhance text generation through iterative refinement. This hybrid approach leverages the strengths of both paradigms: ARLMs excel in fluent, high-quality text generation, while DLMs offer a powerful mechanism for controlled editing and correction.

At a high level, Pipeline operates in two stages:

- Autoregressive Generation: An ARLM produces an initial text output based on a given prompt. This stage ensures efficiency and fluency in generating coherent sequences.
- Diffusion-based Refinement: A diffusion language model takes the ARLM-generated text and iteratively refines it using a secondary conditioning prompt. This allows for correction, alignment, and enhanced controllability while preserving fluency.
To achieve seamless integration, we explore latent-space diffusion, where text representations are iteratively denoised rather than modifying raw tokens directly. This enables smooth, targeted refinements while maintaining contextual consistency. Additionally, we introduce alignment-aware conditioning, where the diffusion model receives both the original prompt and a secondary guidance prompt to enforce desired modifications without excessive drift from the ARLM’s intent.

Our approach balances generation speed, coherence, and flexibility, making it well-suited for applications requiring controllable text generation, post-generation alignment, and iterative text editing. We demonstrate the effectiveness of Pipeline across tasks such as content refinement, bias mitigation, and controlled rewriting, hopefully showing significant improvements over standalone ARLMs.


## Code

To Be Published

  
## Results

To Be Determined


## Future works

## Credits
