
# PE-GPT: a New Paradigm for Power Electronics Design

We lately propose PE-GPT (2024 Sep), **the first multimodal large language model (LLM) specifically designed for power electronics (PE) design**. What impedes the adoption of LLMs in the industry of power electronics mainly includes their limited technical expertise and incapability to process PE-specific data. To address these challenges, PE-GPT is enhanced by retrieval augmented generation (RAG) with customized PE knowledge base, which empowers PE-GPT with PE-specific knowledge and reasoning, while model zoo and simulation repository equip it with the capability of processing PE-specific multi-modal data. Moreover, we propose a hybrid framework that integrates an LLM agent, metaheuristic algorithms, a Model Zoo, and a Simulation Repository. 
<br><br>

<span style="font-size:20px;"><b>Keeping "AI-for-Good" as our mission, PE-GPT strives to revolutionize the paradigm for diverse power electronics design tasks.</b></span>

<br>
Please note: Codes of "Power Electronics GPT (PE-GPT)" will be **progressively** released in the near future!


## The Proposed Hybrid Framework of PE-GPT
![The hybrid framework of PE-GPT.](https://github.com/user-attachments/assets/fa246d51-ea4e-4fce-967f-b584ee5da586)
<br>Fig. 1. The hybrid framework of PE-GPT.


## Demo Videos of PE-GPT
Demo videos of using PE-GPT for the power electronics design tasks.
<br>

Demo Case 1:
  * Modulation Optimization for DAB Converters - 1

https://github.com/user-attachments/assets/53f07316-3a34-411e-86c7-fe621bb5a53c

<br>

Demo Case 2:
  * Modulation Optimization for DAB Converters - 2

https://github.com/user-attachments/assets/7532419a-2819-4fda-98c8-38dfe992708d

<br>

Demo Case 3:
  * Circuit Parameter Design for Buck Converters

https://github.com/user-attachments/assets/2e8ff52e-e2e1-41b5-9825-b0e65e2615c1


## Deploy PE-GPT on your PC
To deploy PE-GPT on your PC, the first step is to setup your API call to OpenAI models, please see core/llm/llm.py for more details.
```bash

# clone the github repository
git clone https://github.com/XinzeLee/PE-GPT

# change the current working directory
cd PE-GPT

# install all required dependencies
pip install -r requirements.txt

# run the GUI and chat with PE-GPT
streamlit run main.py

```
<br><br>

## Reference
@reference: Fanfan Lin, Xinze Li, Weihao Lei, Juan J. Rodriguez-Andina, Josep M. Guerrero, Changyun Wen, Xin Zhang, and Hao Ma, "PE-GPT: a New Paradigm for Power Electronics Design", IEEE Transactions on Industrial Electronics.
<br>
@code-author: Xinze Li, Fanfan Lin

<br><br>
## License

This code is licensed under the [GNU Affero General Public License v3.0 (AGPLv3)](./LICENSE), with additional terms regarding non-commercial use. For more details, see the [Non-Commercial Clause](./NON-COMMERCIAL-CLAUSE.md).

For commercial use, please contact:
1. Xinze Li   (email: xinzeli831@gmail.com );
2. Fanfan Lin (email: fanfanlin31@gmail.com).

