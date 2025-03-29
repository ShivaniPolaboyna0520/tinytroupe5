# tinytroupe5


 Welcome to Codespaces! You are on our default image. 
   - It includes runtimes and tools for Python, Node.js, Docker, and more. See the full list here: https://aka.ms/ghcs-default-image
   - Want to use a custom image instead? Learn more here: https://aka.ms/configure-codespace

🔍 To explore VS Code to its fullest, search using the Command Palette (Cmd/Ctrl + Shift + P or F1).

📝 Edit away, run your app as usual, and we'll automatically make it available for you to access.

@ShivaniPolaboyna0520 ➜ /workspaces/tinytroupe5 (main) $ git clone https://github.com/microsoft/TinyTroupe
Cloning into 'TinyTroupe'...
remote: Enumerating objects: 825, done.
remote: Counting objects: 100% (348/348), done.
remote: Compressing objects: 100% (144/144), done.
remote: Total 825 (delta 287), reused 204 (delta 204), pack-reused 477 (from 1)
Receiving objects: 100% (825/825), 33.25 MiB | 20.46 MiB/s, done.
Resolving deltas: 100% (436/436), done.
@ShivaniPolaboyna0520 ➜ /workspaces/tinytroupe5 (main) $ cd TinyTroupe
@ShivaniPolaboyna0520 ➜ /workspaces/tinytroupe5/TinyTroupe (main) $ pip install . 
Processing /workspaces/tinytroupe5/TinyTroupe
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
  Preparing metadata (pyproject.toml) ... done
Requirement already satisfied: pandas in /home/codespace/.local/lib/python3.12/site-packages (from tinytroupe==0.4.0) (2.2.3)
Collecting pytest (from tinytroupe==0.4.0)
  Downloading pytest-8.3.5-py3-none-any.whl.metadata (7.6 kB)
Collecting pytest-cov (from tinytroupe==0.4.0)
  Downloading pytest_cov-6.0.0-py3-none-any.whl.metadata (27 kB)
Collecting openai>=1.40 (from tinytroupe==0.4.0)
  Downloading openai-1.69.0-py3-none-any.whl.metadata (25 kB)
Collecting tiktoken (from tinytroupe==0.4.0)
  Downloading tiktoken-0.9.0-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (6.7 kB)
Collecting msal (from tinytroupe==0.4.0)
  Downloading msal-1.32.0-py3-none-any.whl.metadata (11 kB)
Collecting rich (from tinytroupe==0.4.0)
  Downloading rich-13.9.4-py3-none-any.whl.metadata (18 kB)
Requirement already satisfied: requests in /home/codespace/.local/lib/python3.12/site-packages (from tinytroupe==0.4.0) (2.32.3)
Collecting chevron (from tinytroupe==0.4.0)
  Downloading chevron-0.14.0-py3-none-any.whl.metadata (4.9 kB)
Collecting llama-index (from tinytroupe==0.4.0)
  Downloading llama_index-0.12.26-py3-none-any.whl.metadata (12 kB)
Collecting llama-index-embeddings-huggingface (from tinytroupe==0.4.0)
  Downloading llama_index_embeddings_huggingface-0.5.2-py3-none-any.whl.metadata (767 bytes)
Collecting llama-index-readers-web (from tinytroupe==0.4.0)
  Downloading llama_index_readers_web-0.3.8-py3-none-any.whl.metadata (1.3 kB)
Collecting llama-index-embeddings-azure-openai (from tinytroupe==0.4.0)
  Downloading llama_index_embeddings_azure_openai-0.3.2-py3-none-any.whl.metadata (794 bytes)
Collecting pypandoc (from tinytroupe==0.4.0)
  Downloading pypandoc-1.15-py3-none-any.whl.metadata (16 kB)
Collecting docx (from tinytroupe==0.4.0)
  Downloading docx-0.2.4.tar.gz (54 kB)
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
  Preparing metadata (pyproject.toml) ... done
Collecting markdown (from tinytroupe==0.4.0)
  Downloading Markdown-3.7-py3-none-any.whl.metadata (7.0 kB)
Collecting jupyter (from tinytroupe==0.4.0)
  Downloading jupyter-1.1.1-py2.py3-none-any.whl.metadata (2.0 kB)
Requirement already satisfied: matplotlib in /home/codespace/.local/lib/python3.12/site-packages (from tinytroupe==0.4.0) (3.10.1)
Collecting pydantic (from tinytroupe==0.4.0)
  Downloading pydantic-2.11.1-py3-none-any.whl.metadata (63 kB)
Requirement already satisfied: anyio<5,>=3.5.0 in /home/codespace/.local/lib/python3.12/site-packages (from openai>=1.40->tinytroupe==0.4.0) (4.9.0)
Collecting distro<2,>=1.7.0 (from openai>=1.40->tinytroupe==0.4.0)
  Downloading distro-1.9.0-py3-none-any.whl.metadata (6.8 kB)
Requirement already satisfied: httpx<1,>=0.23.0 in /home/codespace/.local/lib/python3.12/site-packages (from openai>=1.40->tinytroupe==0.4.0) (0.28.1)
Collecting jiter<1,>=0.4.0 (from openai>=1.40->tinytroupe==0.4.0)
  Downloading jiter-0.9.0-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (5.2 kB)
Requirement already satisfied: sniffio in /home/codespace/.local/lib/python3.12/site-packages (from openai>=1.40->tinytroupe==0.4.0) (1.3.1)
Collecting tqdm>4 (from openai>=1.40->tinytroupe==0.4.0)
  Downloading tqdm-4.67.1-py3-none-any.whl.metadata (57 kB)
Requirement already satisfied: typing-extensions<5,>=4.11 in /home/codespace/.local/lib/python3.12/site-packages (from openai>=1.40->tinytroupe==0.4.0) (4.12.2)
Collecting annotated-types>=0.6.0 (from pydantic->tinytroupe==0.4.0)
  Downloading annotated_types-0.7.0-py3-none-any.whl.metadata (15 kB)
Collecting pydantic-core==2.33.0 (from pydantic->tinytroupe==0.4.0)
  Downloading pydantic_core-2.33.0-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (6.8 kB)
Collecting typing-inspection>=0.4.0 (from pydantic->tinytroupe==0.4.0)
  Downloading typing_inspection-0.4.0-py3-none-any.whl.metadata (2.6 kB)
Collecting lxml (from docx->tinytroupe==0.4.0)
  Downloading lxml-5.3.1-cp312-cp312-manylinux_2_28_x86_64.whl.metadata (3.7 kB)
Requirement already satisfied: Pillow>=2.0 in /home/codespace/.local/lib/python3.12/site-packages (from docx->tinytroupe==0.4.0) (11.1.0)
Collecting notebook (from jupyter->tinytroupe==0.4.0)
  Downloading notebook-7.3.3-py3-none-any.whl.metadata (10 kB)
Collecting jupyter-console (from jupyter->tinytroupe==0.4.0)
  Downloading jupyter_console-6.6.3-py3-none-any.whl.metadata (5.8 kB)
Requirement already satisfied: nbconvert in /home/codespace/.local/lib/python3.12/site-packages (from jupyter->tinytroupe==0.4.0) (7.16.6)
Requirement already satisfied: ipykernel in /home/codespace/.local/lib/python3.12/site-packages (from jupyter->tinytroupe==0.4.0) (6.29.5)
Collecting ipywidgets (from jupyter->tinytroupe==0.4.0)
  Downloading ipywidgets-8.1.5-py3-none-any.whl.metadata (2.3 kB)
Requirement already satisfied: jupyterlab in /home/codespace/.local/lib/python3.12/site-packages (from jupyter->tinytroupe==0.4.0) (4.3.6)
Collecting llama-index-agent-openai<0.5.0,>=0.4.0 (from llama-index->tinytroupe==0.4.0)
  Downloading llama_index_agent_openai-0.4.6-py3-none-any.whl.metadata (727 bytes)
Collecting llama-index-cli<0.5.0,>=0.4.1 (from llama-index->tinytroupe==0.4.0)
  Downloading llama_index_cli-0.4.1-py3-none-any.whl.metadata (1.5 kB)
Collecting llama-index-core<0.13.0,>=0.12.26 (from llama-index->tinytroupe==0.4.0)
  Downloading llama_index_core-0.12.27-py3-none-any.whl.metadata (2.6 kB)
Collecting llama-index-embeddings-openai<0.4.0,>=0.3.0 (from llama-index->tinytroupe==0.4.0)
  Downloading llama_index_embeddings_openai-0.3.1-py3-none-any.whl.metadata (684 bytes)
Collecting llama-index-indices-managed-llama-cloud>=0.4.0 (from llama-index->tinytroupe==0.4.0)
  Downloading llama_index_indices_managed_llama_cloud-0.6.9-py3-none-any.whl.metadata (3.6 kB)
Collecting llama-index-llms-openai<0.4.0,>=0.3.0 (from llama-index->tinytroupe==0.4.0)
  Downloading llama_index_llms_openai-0.3.29-py3-none-any.whl.metadata (3.3 kB)
Collecting llama-index-multi-modal-llms-openai<0.5.0,>=0.4.0 (from llama-index->tinytroupe==0.4.0)
  Downloading llama_index_multi_modal_llms_openai-0.4.3-py3-none-any.whl.metadata (726 bytes)
Collecting llama-index-program-openai<0.4.0,>=0.3.0 (from llama-index->tinytroupe==0.4.0)
  Downloading llama_index_program_openai-0.3.1-py3-none-any.whl.metadata (764 bytes)
Collecting llama-index-question-gen-openai<0.4.0,>=0.3.0 (from llama-index->tinytroupe==0.4.0)
  Downloading llama_index_question_gen_openai-0.3.0-py3-none-any.whl.metadata (783 bytes)
Collecting llama-index-readers-file<0.5.0,>=0.4.0 (from llama-index->tinytroupe==0.4.0)
  Downloading llama_index_readers_file-0.4.7-py3-none-any.whl.metadata (5.4 kB)
Collecting llama-index-readers-llama-parse>=0.4.0 (from llama-index->tinytroupe==0.4.0)
  Downloading llama_index_readers_llama_parse-0.4.0-py3-none-any.whl.metadata (3.6 kB)
Collecting nltk>3.8.1 (from llama-index->tinytroupe==0.4.0)
  Downloading nltk-3.9.1-py3-none-any.whl.metadata (2.9 kB)
Collecting llama-index-llms-azure-openai<0.4.0,>=0.3.0 (from llama-index-embeddings-azure-openai->tinytroupe==0.4.0)
  Downloading llama_index_llms_azure_openai-0.3.2-py3-none-any.whl.metadata (4.0 kB)
Collecting huggingface-hub>=0.19.0 (from huggingface-hub[inference]>=0.19.0->llama-index-embeddings-huggingface->tinytroupe==0.4.0)
  Downloading huggingface_hub-0.29.3-py3-none-any.whl.metadata (13 kB)
Collecting sentence-transformers>=2.6.1 (from llama-index-embeddings-huggingface->tinytroupe==0.4.0)
  Downloading sentence_transformers-4.0.1-py3-none-any.whl.metadata (13 kB)
Collecting aiohttp<4.0.0,>=3.9.1 (from llama-index-readers-web->tinytroupe==0.4.0)
  Downloading aiohttp-3.11.14-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (7.7 kB)
Requirement already satisfied: beautifulsoup4<5.0.0,>=4.12.3 in /home/codespace/.local/lib/python3.12/site-packages (from llama-index-readers-web->tinytroupe==0.4.0) (4.13.3)
Collecting chromedriver-autoinstaller<0.7.0,>=0.6.3 (from llama-index-readers-web->tinytroupe==0.4.0)
  Downloading chromedriver_autoinstaller-0.6.4-py3-none-any.whl.metadata (2.1 kB)
Collecting html2text<2025.0.0,>=2024.2.26 (from llama-index-readers-web->tinytroupe==0.4.0)
  Downloading html2text-2024.2.26.tar.gz (56 kB)
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
  Preparing metadata (pyproject.toml) ... done
Collecting newspaper3k<0.3.0,>=0.2.8 (from llama-index-readers-web->tinytroupe==0.4.0)
  Downloading newspaper3k-0.2.8-py3-none-any.whl.metadata (11 kB)
Collecting playwright<2.0,>=1.30 (from llama-index-readers-web->tinytroupe==0.4.0)
  Downloading playwright-1.51.0-py3-none-manylinux1_x86_64.whl.metadata (3.5 kB)
Collecting selenium<5.0.0,>=4.17.2 (from llama-index-readers-web->tinytroupe==0.4.0)
  Downloading selenium-4.30.0-py3-none-any.whl.metadata (7.5 kB)
Collecting spider-client<0.0.28,>=0.0.27 (from llama-index-readers-web->tinytroupe==0.4.0)
  Downloading spider-client-0.0.27.tar.gz (5.8 kB)
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
  Preparing metadata (pyproject.toml) ... done
Requirement already satisfied: urllib3>=1.1.0 in /home/codespace/.local/lib/python3.12/site-packages (from llama-index-readers-web->tinytroupe==0.4.0) (2.3.0)
Requirement already satisfied: charset-normalizer<4,>=2 in /home/codespace/.local/lib/python3.12/site-packages (from requests->tinytroupe==0.4.0) (3.4.1)
Requirement already satisfied: idna<4,>=2.5 in /home/codespace/.local/lib/python3.12/site-packages (from requests->tinytroupe==0.4.0) (3.10)
Requirement already satisfied: certifi>=2017.4.17 in /home/codespace/.local/lib/python3.12/site-packages (from requests->tinytroupe==0.4.0) (2025.1.31)
Requirement already satisfied: contourpy>=1.0.1 in /home/codespace/.local/lib/python3.12/site-packages (from matplotlib->tinytroupe==0.4.0) (1.3.1)
Requirement already satisfied: cycler>=0.10 in /home/codespace/.local/lib/python3.12/site-packages (from matplotlib->tinytroupe==0.4.0) (0.12.1)
Requirement already satisfied: fonttools>=4.22.0 in /home/codespace/.local/lib/python3.12/site-packages (from matplotlib->tinytroupe==0.4.0) (4.56.0)
Requirement already satisfied: kiwisolver>=1.3.1 in /home/codespace/.local/lib/python3.12/site-packages (from matplotlib->tinytroupe==0.4.0) (1.4.8)
Requirement already satisfied: numpy>=1.23 in /home/codespace/.local/lib/python3.12/site-packages (from matplotlib->tinytroupe==0.4.0) (2.2.4)
Requirement already satisfied: packaging>=20.0 in /home/codespace/.local/lib/python3.12/site-packages (from matplotlib->tinytroupe==0.4.0) (24.2)
Requirement already satisfied: pyparsing>=2.3.1 in /home/codespace/.local/lib/python3.12/site-packages (from matplotlib->tinytroupe==0.4.0) (3.2.1)
Requirement already satisfied: python-dateutil>=2.7 in /home/codespace/.local/lib/python3.12/site-packages (from matplotlib->tinytroupe==0.4.0) (2.9.0.post0)
Collecting PyJWT<3,>=1.0.0 (from PyJWT[crypto]<3,>=1.0.0->msal->tinytroupe==0.4.0)
  Downloading PyJWT-2.10.1-py3-none-any.whl.metadata (4.0 kB)
Collecting cryptography<47,>=2.5 (from msal->tinytroupe==0.4.0)
  Using cached cryptography-44.0.2-cp39-abi3-manylinux_2_28_x86_64.whl.metadata (5.7 kB)
Requirement already satisfied: pytz>=2020.1 in /home/codespace/.local/lib/python3.12/site-packages (from pandas->tinytroupe==0.4.0) (2025.1)
Requirement already satisfied: tzdata>=2022.7 in /home/codespace/.local/lib/python3.12/site-packages (from pandas->tinytroupe==0.4.0) (2025.1)
Collecting iniconfig (from pytest->tinytroupe==0.4.0)
  Downloading iniconfig-2.1.0-py3-none-any.whl.metadata (2.7 kB)
Collecting pluggy<2,>=1.5 (from pytest->tinytroupe==0.4.0)
  Downloading pluggy-1.5.0-py3-none-any.whl.metadata (4.8 kB)
Collecting coverage>=7.5 (from coverage[toml]>=7.5->pytest-cov->tinytroupe==0.4.0)
  Downloading coverage-7.7.1-cp312-cp312-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (8.5 kB)
Collecting markdown-it-py>=2.2.0 (from rich->tinytroupe==0.4.0)
  Downloading markdown_it_py-3.0.0-py3-none-any.whl.metadata (6.9 kB)
Requirement already satisfied: pygments<3.0.0,>=2.13.0 in /home/codespace/.local/lib/python3.12/site-packages (from rich->tinytroupe==0.4.0) (2.19.1)
Collecting regex>=2022.1.18 (from tiktoken->tinytroupe==0.4.0)
  Downloading regex-2024.11.6-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (40 kB)
Collecting aiohappyeyeballs>=2.3.0 (from aiohttp<4.0.0,>=3.9.1->llama-index-readers-web->tinytroupe==0.4.0)
  Downloading aiohappyeyeballs-2.6.1-py3-none-any.whl.metadata (5.9 kB)
Collecting aiosignal>=1.1.2 (from aiohttp<4.0.0,>=3.9.1->llama-index-readers-web->tinytroupe==0.4.0)
  Downloading aiosignal-1.3.2-py2.py3-none-any.whl.metadata (3.8 kB)
Requirement already satisfied: attrs>=17.3.0 in /home/codespace/.local/lib/python3.12/site-packages (from aiohttp<4.0.0,>=3.9.1->llama-index-readers-web->tinytroupe==0.4.0) (25.3.0)
Collecting frozenlist>=1.1.1 (from aiohttp<4.0.0,>=3.9.1->llama-index-readers-web->tinytroupe==0.4.0)
  Downloading frozenlist-1.5.0-cp312-cp312-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (13 kB)
Collecting multidict<7.0,>=4.5 (from aiohttp<4.0.0,>=3.9.1->llama-index-readers-web->tinytroupe==0.4.0)
  Downloading multidict-6.2.0-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (4.9 kB)
Collecting propcache>=0.2.0 (from aiohttp<4.0.0,>=3.9.1->llama-index-readers-web->tinytroupe==0.4.0)
  Downloading propcache-0.3.1-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (10 kB)
Collecting yarl<2.0,>=1.17.0 (from aiohttp<4.0.0,>=3.9.1->llama-index-readers-web->tinytroupe==0.4.0)
  Downloading yarl-1.18.3-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (69 kB)
Requirement already satisfied: soupsieve>1.2 in /home/codespace/.local/lib/python3.12/site-packages (from beautifulsoup4<5.0.0,>=4.12.3->llama-index-readers-web->tinytroupe==0.4.0) (2.6)
Requirement already satisfied: cffi>=1.12 in /home/codespace/.local/lib/python3.12/site-packages (from cryptography<47,>=2.5->msal->tinytroupe==0.4.0) (1.17.1)
Requirement already satisfied: httpcore==1.* in /home/codespace/.local/lib/python3.12/site-packages (from httpx<1,>=0.23.0->openai>=1.40->tinytroupe==0.4.0) (1.0.7)
Requirement already satisfied: h11<0.15,>=0.13 in /home/codespace/.local/lib/python3.12/site-packages (from httpcore==1.*->httpx<1,>=0.23.0->openai>=1.40->tinytroupe==0.4.0) (0.14.0)
Requirement already satisfied: filelock in /home/codespace/.local/lib/python3.12/site-packages (from huggingface-hub>=0.19.0->huggingface-hub[inference]>=0.19.0->llama-index-embeddings-huggingface->tinytroupe==0.4.0) (3.13.1)
Requirement already satisfied: fsspec>=2023.5.0 in /home/codespace/.local/lib/python3.12/site-packages (from huggingface-hub>=0.19.0->huggingface-hub[inference]>=0.19.0->llama-index-embeddings-huggingface->tinytroupe==0.4.0) (2024.6.1)
Requirement already satisfied: pyyaml>=5.1 in /home/codespace/.local/lib/python3.12/site-packages (from huggingface-hub>=0.19.0->huggingface-hub[inference]>=0.19.0->llama-index-embeddings-huggingface->tinytroupe==0.4.0) (6.0.2)
Collecting SQLAlchemy>=1.4.49 (from SQLAlchemy[asyncio]>=1.4.49->llama-index-core<0.13.0,>=0.12.26->llama-index->tinytroupe==0.4.0)
  Downloading sqlalchemy-2.0.40-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (9.6 kB)
Collecting banks<3.0.0,>=2.0.0 (from llama-index-core<0.13.0,>=0.12.26->llama-index->tinytroupe==0.4.0)
  Downloading banks-2.1.0-py3-none-any.whl.metadata (11 kB)
Collecting dataclasses-json (from llama-index-core<0.13.0,>=0.12.26->llama-index->tinytroupe==0.4.0)
  Downloading dataclasses_json-0.6.7-py3-none-any.whl.metadata (25 kB)
Collecting deprecated>=1.2.9.3 (from llama-index-core<0.13.0,>=0.12.26->llama-index->tinytroupe==0.4.0)
  Downloading Deprecated-1.2.18-py2.py3-none-any.whl.metadata (5.7 kB)
Collecting dirtyjson<2.0.0,>=1.0.8 (from llama-index-core<0.13.0,>=0.12.26->llama-index->tinytroupe==0.4.0)
  Downloading dirtyjson-1.0.8-py3-none-any.whl.metadata (11 kB)
Collecting filetype<2.0.0,>=1.2.0 (from llama-index-core<0.13.0,>=0.12.26->llama-index->tinytroupe==0.4.0)
  Downloading filetype-1.2.0-py2.py3-none-any.whl.metadata (6.5 kB)
Requirement already satisfied: nest-asyncio<2.0.0,>=1.5.8 in /home/codespace/.local/lib/python3.12/site-packages (from llama-index-core<0.13.0,>=0.12.26->llama-index->tinytroupe==0.4.0) (1.6.0)
Requirement already satisfied: networkx>=3.0 in /home/codespace/.local/lib/python3.12/site-packages (from llama-index-core<0.13.0,>=0.12.26->llama-index->tinytroupe==0.4.0) (3.3)
Collecting tenacity!=8.4.0,<10.0.0,>=8.2.0 (from llama-index-core<0.13.0,>=0.12.26->llama-index->tinytroupe==0.4.0)
  Downloading tenacity-9.0.0-py3-none-any.whl.metadata (1.2 kB)
Collecting typing-inspect>=0.8.0 (from llama-index-core<0.13.0,>=0.12.26->llama-index->tinytroupe==0.4.0)
  Downloading typing_inspect-0.9.0-py3-none-any.whl.metadata (1.5 kB)
Collecting wrapt (from llama-index-core<0.13.0,>=0.12.26->llama-index->tinytroupe==0.4.0)
  Downloading wrapt-1.17.2-cp312-cp312-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (6.4 kB)
Collecting llama-cloud<0.2.0,>=0.1.13 (from llama-index-indices-managed-llama-cloud>=0.4.0->llama-index->tinytroupe==0.4.0)
  Downloading llama_cloud-0.1.17-py3-none-any.whl.metadata (902 bytes)
Collecting azure-identity<2.0.0,>=1.15.0 (from llama-index-llms-azure-openai<0.4.0,>=0.3.0->llama-index-embeddings-azure-openai->tinytroupe==0.4.0)
  Downloading azure_identity-1.21.0-py3-none-any.whl.metadata (81 kB)
Collecting pypdf<6.0.0,>=5.1.0 (from llama-index-readers-file<0.5.0,>=0.4.0->llama-index->tinytroupe==0.4.0)
  Downloading pypdf-5.4.0-py3-none-any.whl.metadata (7.3 kB)
Collecting striprtf<0.0.27,>=0.0.26 (from llama-index-readers-file<0.5.0,>=0.4.0->llama-index->tinytroupe==0.4.0)
  Downloading striprtf-0.0.26-py3-none-any.whl.metadata (2.1 kB)
Collecting llama-parse>=0.5.0 (from llama-index-readers-llama-parse>=0.4.0->llama-index->tinytroupe==0.4.0)
  Downloading llama_parse-0.6.4.post1-py3-none-any.whl.metadata (6.9 kB)
Collecting mdurl~=0.1 (from markdown-it-py>=2.2.0->rich->tinytroupe==0.4.0)
  Downloading mdurl-0.1.2-py3-none-any.whl.metadata (1.6 kB)
Collecting cssselect>=0.9.2 (from newspaper3k<0.3.0,>=0.2.8->llama-index-readers-web->tinytroupe==0.4.0)
  Downloading cssselect-1.3.0-py3-none-any.whl.metadata (2.6 kB)
Collecting feedparser>=5.2.1 (from newspaper3k<0.3.0,>=0.2.8->llama-index-readers-web->tinytroupe==0.4.0)
  Downloading feedparser-6.0.11-py3-none-any.whl.metadata (2.4 kB)
Collecting tldextract>=2.0.1 (from newspaper3k<0.3.0,>=0.2.8->llama-index-readers-web->tinytroupe==0.4.0)
  Downloading tldextract-5.1.3-py3-none-any.whl.metadata (11 kB)
Collecting feedfinder2>=0.0.4 (from newspaper3k<0.3.0,>=0.2.8->llama-index-readers-web->tinytroupe==0.4.0)
  Downloading feedfinder2-0.0.4.tar.gz (3.3 kB)
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
  Preparing metadata (pyproject.toml) ... done
Collecting jieba3k>=0.35.1 (from newspaper3k<0.3.0,>=0.2.8->llama-index-readers-web->tinytroupe==0.4.0)
  Downloading jieba3k-0.35.1.zip (7.4 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 7.4/7.4 MB 42.1 MB/s eta 0:00:00
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
  Preparing metadata (pyproject.toml) ... done
Collecting tinysegmenter==0.3 (from newspaper3k<0.3.0,>=0.2.8->llama-index-readers-web->tinytroupe==0.4.0)
  Downloading tinysegmenter-0.3.tar.gz (16 kB)
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
  Preparing metadata (pyproject.toml) ... done
Collecting click (from nltk>3.8.1->llama-index->tinytroupe==0.4.0)
  Downloading click-8.1.8-py3-none-any.whl.metadata (2.3 kB)
Requirement already satisfied: joblib in /home/codespace/.local/lib/python3.12/site-packages (from nltk>3.8.1->llama-index->tinytroupe==0.4.0) (1.4.2)
Collecting pyee<13,>=12 (from playwright<2.0,>=1.30->llama-index-readers-web->tinytroupe==0.4.0)
  Downloading pyee-12.1.1-py3-none-any.whl.metadata (2.9 kB)
Collecting greenlet<4.0.0,>=3.1.1 (from playwright<2.0,>=1.30->llama-index-readers-web->tinytroupe==0.4.0)
  Downloading greenlet-3.1.1-cp312-cp312-manylinux_2_24_x86_64.manylinux_2_28_x86_64.whl.metadata (3.8 kB)
Requirement already satisfied: six>=1.5 in /home/codespace/.local/lib/python3.12/site-packages (from python-dateutil>=2.7->matplotlib->tinytroupe==0.4.0) (1.17.0)
Collecting trio~=0.17 (from selenium<5.0.0,>=4.17.2->llama-index-readers-web->tinytroupe==0.4.0)
  Downloading trio-0.29.0-py3-none-any.whl.metadata (8.5 kB)
Collecting trio-websocket~=0.9 (from selenium<5.0.0,>=4.17.2->llama-index-readers-web->tinytroupe==0.4.0)
  Downloading trio_websocket-0.12.2-py3-none-any.whl.metadata (5.1 kB)
Requirement already satisfied: websocket-client~=1.8 in /home/codespace/.local/lib/python3.12/site-packages (from selenium<5.0.0,>=4.17.2->llama-index-readers-web->tinytroupe==0.4.0) (1.8.0)
Collecting transformers<5.0.0,>=4.41.0 (from sentence-transformers>=2.6.1->llama-index-embeddings-huggingface->tinytroupe==0.4.0)
  Downloading transformers-4.50.3-py3-none-any.whl.metadata (39 kB)
Requirement already satisfied: torch>=1.11.0 in /home/codespace/.local/lib/python3.12/site-packages (from sentence-transformers>=2.6.1->llama-index-embeddings-huggingface->tinytroupe==0.4.0) (2.6.0+cpu)
Requirement already satisfied: scikit-learn in /home/codespace/.local/lib/python3.12/site-packages (from sentence-transformers>=2.6.1->llama-index-embeddings-huggingface->tinytroupe==0.4.0) (1.6.1)
Requirement already satisfied: scipy in /home/codespace/.local/lib/python3.12/site-packages (from sentence-transformers>=2.6.1->llama-index-embeddings-huggingface->tinytroupe==0.4.0) (1.15.2)
Requirement already satisfied: comm>=0.1.1 in /home/codespace/.local/lib/python3.12/site-packages (from ipykernel->jupyter->tinytroupe==0.4.0) (0.2.2)
Requirement already satisfied: debugpy>=1.6.5 in /home/codespace/.local/lib/python3.12/site-packages (from ipykernel->jupyter->tinytroupe==0.4.0) (1.8.13)
Requirement already satisfied: ipython>=7.23.1 in /home/codespace/.local/lib/python3.12/site-packages (from ipykernel->jupyter->tinytroupe==0.4.0) (9.0.2)
Requirement already satisfied: jupyter-client>=6.1.12 in /home/codespace/.local/lib/python3.12/site-packages (from ipykernel->jupyter->tinytroupe==0.4.0) (8.6.3)
Requirement already satisfied: jupyter-core!=5.0.*,>=4.12 in /home/codespace/.local/lib/python3.12/site-packages (from ipykernel->jupyter->tinytroupe==0.4.0) (5.7.2)
Requirement already satisfied: matplotlib-inline>=0.1 in /home/codespace/.local/lib/python3.12/site-packages (from ipykernel->jupyter->tinytroupe==0.4.0) (0.1.7)
Requirement already satisfied: psutil in /home/codespace/.local/lib/python3.12/site-packages (from ipykernel->jupyter->tinytroupe==0.4.0) (7.0.0)
Requirement already satisfied: pyzmq>=24 in /home/codespace/.local/lib/python3.12/site-packages (from ipykernel->jupyter->tinytroupe==0.4.0) (26.3.0)
Requirement already satisfied: tornado>=6.1 in /home/codespace/.local/lib/python3.12/site-packages (from ipykernel->jupyter->tinytroupe==0.4.0) (6.4.2)
Requirement already satisfied: traitlets>=5.4.0 in /home/codespace/.local/lib/python3.12/site-packages (from ipykernel->jupyter->tinytroupe==0.4.0) (5.14.3)
Collecting widgetsnbextension~=4.0.12 (from ipywidgets->jupyter->tinytroupe==0.4.0)
  Downloading widgetsnbextension-4.0.13-py3-none-any.whl.metadata (1.6 kB)
Collecting jupyterlab-widgets~=3.0.12 (from ipywidgets->jupyter->tinytroupe==0.4.0)
  Downloading jupyterlab_widgets-3.0.13-py3-none-any.whl.metadata (4.1 kB)
Requirement already satisfied: prompt-toolkit>=3.0.30 in /home/codespace/.local/lib/python3.12/site-packages (from jupyter-console->jupyter->tinytroupe==0.4.0) (3.0.50)
Requirement already satisfied: async-lru>=1.0.0 in /home/codespace/.local/lib/python3.12/site-packages (from jupyterlab->jupyter->tinytroupe==0.4.0) (2.0.5)
Requirement already satisfied: jinja2>=3.0.3 in /home/codespace/.local/lib/python3.12/site-packages (from jupyterlab->jupyter->tinytroupe==0.4.0) (3.1.6)
Requirement already satisfied: jupyter-lsp>=2.0.0 in /home/codespace/.local/lib/python3.12/site-packages (from jupyterlab->jupyter->tinytroupe==0.4.0) (2.2.5)
Requirement already satisfied: jupyter-server<3,>=2.4.0 in /home/codespace/.local/lib/python3.12/site-packages (from jupyterlab->jupyter->tinytroupe==0.4.0) (2.15.0)
Requirement already satisfied: jupyterlab-server<3,>=2.27.1 in /home/codespace/.local/lib/python3.12/site-packages (from jupyterlab->jupyter->tinytroupe==0.4.0) (2.27.3)
Requirement already satisfied: notebook-shim>=0.2 in /home/codespace/.local/lib/python3.12/site-packages (from jupyterlab->jupyter->tinytroupe==0.4.0) (0.2.4)
Requirement already satisfied: setuptools>=40.8.0 in /home/codespace/.local/lib/python3.12/site-packages (from jupyterlab->jupyter->tinytroupe==0.4.0) (76.0.0)
Requirement already satisfied: bleach!=5.0.0 in /home/codespace/.local/lib/python3.12/site-packages (from bleach[css]!=5.0.0->nbconvert->jupyter->tinytroupe==0.4.0) (6.2.0)
Requirement already satisfied: defusedxml in /home/codespace/.local/lib/python3.12/site-packages (from nbconvert->jupyter->tinytroupe==0.4.0) (0.7.1)
Requirement already satisfied: jupyterlab-pygments in /home/codespace/.local/lib/python3.12/site-packages (from nbconvert->jupyter->tinytroupe==0.4.0) (0.3.0)
Requirement already satisfied: markupsafe>=2.0 in /home/codespace/.local/lib/python3.12/site-packages (from nbconvert->jupyter->tinytroupe==0.4.0) (3.0.2)
Requirement already satisfied: mistune<4,>=2.0.3 in /home/codespace/.local/lib/python3.12/site-packages (from nbconvert->jupyter->tinytroupe==0.4.0) (3.1.2)
Requirement already satisfied: nbclient>=0.5.0 in /home/codespace/.local/lib/python3.12/site-packages (from nbconvert->jupyter->tinytroupe==0.4.0) (0.10.2)
Requirement already satisfied: nbformat>=5.7 in /home/codespace/.local/lib/python3.12/site-packages (from nbconvert->jupyter->tinytroupe==0.4.0) (5.10.4)
Requirement already satisfied: pandocfilters>=1.4.1 in /home/codespace/.local/lib/python3.12/site-packages (from nbconvert->jupyter->tinytroupe==0.4.0) (1.5.1)
Collecting azure-core>=1.31.0 (from azure-identity<2.0.0,>=1.15.0->llama-index-llms-azure-openai<0.4.0,>=0.3.0->llama-index-embeddings-azure-openai->tinytroupe==0.4.0)
  Downloading azure_core-1.32.0-py3-none-any.whl.metadata (39 kB)
Collecting msal-extensions>=1.2.0 (from azure-identity<2.0.0,>=1.15.0->llama-index-llms-azure-openai<0.4.0,>=0.3.0->llama-index-embeddings-azure-openai->tinytroupe==0.4.0)
  Downloading msal_extensions-1.3.1-py3-none-any.whl.metadata (7.8 kB)
Collecting griffe (from banks<3.0.0,>=2.0.0->llama-index-core<0.13.0,>=0.12.26->llama-index->tinytroupe==0.4.0)
  Downloading griffe-1.7.1-py3-none-any.whl.metadata (5.0 kB)
Requirement already satisfied: webencodings in /home/codespace/.local/lib/python3.12/site-packages (from bleach!=5.0.0->bleach[css]!=5.0.0->nbconvert->jupyter->tinytroupe==0.4.0) (0.5.1)
Requirement already satisfied: tinycss2<1.5,>=1.1.0 in /home/codespace/.local/lib/python3.12/site-packages (from bleach[css]!=5.0.0->nbconvert->jupyter->tinytroupe==0.4.0) (1.4.0)
Requirement already satisfied: pycparser in /home/codespace/.local/lib/python3.12/site-packages (from cffi>=1.12->cryptography<47,>=2.5->msal->tinytroupe==0.4.0) (2.22)
Collecting sgmllib3k (from feedparser>=5.2.1->newspaper3k<0.3.0,>=0.2.8->llama-index-readers-web->tinytroupe==0.4.0)
  Downloading sgmllib3k-1.0.0.tar.gz (5.8 kB)
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
  Preparing metadata (pyproject.toml) ... done
Requirement already satisfied: decorator in /home/codespace/.local/lib/python3.12/site-packages (from ipython>=7.23.1->ipykernel->jupyter->tinytroupe==0.4.0) (5.2.1)
Requirement already satisfied: ipython-pygments-lexers in /home/codespace/.local/lib/python3.12/site-packages (from ipython>=7.23.1->ipykernel->jupyter->tinytroupe==0.4.0) (1.1.1)
Requirement already satisfied: jedi>=0.16 in /home/codespace/.local/lib/python3.12/site-packages (from ipython>=7.23.1->ipykernel->jupyter->tinytroupe==0.4.0) (0.19.2)
Requirement already satisfied: pexpect>4.3 in /home/codespace/.local/lib/python3.12/site-packages (from ipython>=7.23.1->ipykernel->jupyter->tinytroupe==0.4.0) (4.9.0)
Requirement already satisfied: stack_data in /home/codespace/.local/lib/python3.12/site-packages (from ipython>=7.23.1->ipykernel->jupyter->tinytroupe==0.4.0) (0.6.3)
Requirement already satisfied: platformdirs>=2.5 in /home/codespace/.local/lib/python3.12/site-packages (from jupyter-core!=5.0.*,>=4.12->ipykernel->jupyter->tinytroupe==0.4.0) (4.3.6)
Requirement already satisfied: argon2-cffi>=21.1 in /home/codespace/.local/lib/python3.12/site-packages (from jupyter-server<3,>=2.4.0->jupyterlab->jupyter->tinytroupe==0.4.0) (23.1.0)
Requirement already satisfied: jupyter-events>=0.11.0 in /home/codespace/.local/lib/python3.12/site-packages (from jupyter-server<3,>=2.4.0->jupyterlab->jupyter->tinytroupe==0.4.0) (0.12.0)
Requirement already satisfied: jupyter-server-terminals>=0.4.4 in /home/codespace/.local/lib/python3.12/site-packages (from jupyter-server<3,>=2.4.0->jupyterlab->jupyter->tinytroupe==0.4.0) (0.5.3)
Requirement already satisfied: overrides>=5.0 in /home/codespace/.local/lib/python3.12/site-packages (from jupyter-server<3,>=2.4.0->jupyterlab->jupyter->tinytroupe==0.4.0) (7.7.0)
Requirement already satisfied: prometheus-client>=0.9 in /home/codespace/.local/lib/python3.12/site-packages (from jupyter-server<3,>=2.4.0->jupyterlab->jupyter->tinytroupe==0.4.0) (0.21.1)
Requirement already satisfied: send2trash>=1.8.2 in /home/codespace/.local/lib/python3.12/site-packages (from jupyter-server<3,>=2.4.0->jupyterlab->jupyter->tinytroupe==0.4.0) (1.8.3)
Requirement already satisfied: terminado>=0.8.3 in /home/codespace/.local/lib/python3.12/site-packages (from jupyter-server<3,>=2.4.0->jupyterlab->jupyter->tinytroupe==0.4.0) (0.18.1)
Requirement already satisfied: babel>=2.10 in /home/codespace/.local/lib/python3.12/site-packages (from jupyterlab-server<3,>=2.27.1->jupyterlab->jupyter->tinytroupe==0.4.0) (2.17.0)
Requirement already satisfied: json5>=0.9.0 in /home/codespace/.local/lib/python3.12/site-packages (from jupyterlab-server<3,>=2.27.1->jupyterlab->jupyter->tinytroupe==0.4.0) (0.10.0)
Requirement already satisfied: jsonschema>=4.18.0 in /home/codespace/.local/lib/python3.12/site-packages (from jupyterlab-server<3,>=2.27.1->jupyterlab->jupyter->tinytroupe==0.4.0) (4.23.0)
Collecting llama-cloud-services>=0.6.4 (from llama-parse>=0.5.0->llama-index-readers-llama-parse>=0.4.0->llama-index->tinytroupe==0.4.0)
  Downloading llama_cloud_services-0.6.9-py3-none-any.whl.metadata (2.9 kB)
Requirement already satisfied: fastjsonschema>=2.15 in /home/codespace/.local/lib/python3.12/site-packages (from nbformat>=5.7->nbconvert->jupyter->tinytroupe==0.4.0) (2.21.1)
Requirement already satisfied: wcwidth in /home/codespace/.local/lib/python3.12/site-packages (from prompt-toolkit>=3.0.30->jupyter-console->jupyter->tinytroupe==0.4.0) (0.2.13)
Collecting requests-file>=1.4 (from tldextract>=2.0.1->newspaper3k<0.3.0,>=0.2.8->llama-index-readers-web->tinytroupe==0.4.0)
  Downloading requests_file-2.1.0-py2.py3-none-any.whl.metadata (1.7 kB)
Requirement already satisfied: sympy==1.13.1 in /home/codespace/.local/lib/python3.12/site-packages (from torch>=1.11.0->sentence-transformers>=2.6.1->llama-index-embeddings-huggingface->tinytroupe==0.4.0) (1.13.1)
Requirement already satisfied: mpmath<1.4,>=1.1.0 in /home/codespace/.local/lib/python3.12/site-packages (from sympy==1.13.1->torch>=1.11.0->sentence-transformers>=2.6.1->llama-index-embeddings-huggingface->tinytroupe==0.4.0) (1.3.0)
Collecting tokenizers<0.22,>=0.21 (from transformers<5.0.0,>=4.41.0->sentence-transformers>=2.6.1->llama-index-embeddings-huggingface->tinytroupe==0.4.0)
  Downloading tokenizers-0.21.1-cp39-abi3-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (6.8 kB)
Collecting safetensors>=0.4.3 (from transformers<5.0.0,>=4.41.0->sentence-transformers>=2.6.1->llama-index-embeddings-huggingface->tinytroupe==0.4.0)
  Downloading safetensors-0.5.3-cp38-abi3-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (3.8 kB)
Collecting sortedcontainers (from trio~=0.17->selenium<5.0.0,>=4.17.2->llama-index-readers-web->tinytroupe==0.4.0)
  Downloading sortedcontainers-2.4.0-py2.py3-none-any.whl.metadata (10 kB)
Collecting outcome (from trio~=0.17->selenium<5.0.0,>=4.17.2->llama-index-readers-web->tinytroupe==0.4.0)
  Downloading outcome-1.3.0.post0-py2.py3-none-any.whl.metadata (2.6 kB)
Collecting wsproto>=0.14 (from trio-websocket~=0.9->selenium<5.0.0,>=4.17.2->llama-index-readers-web->tinytroupe==0.4.0)
  Downloading wsproto-1.2.0-py3-none-any.whl.metadata (5.6 kB)
Collecting mypy-extensions>=0.3.0 (from typing-inspect>=0.8.0->llama-index-core<0.13.0,>=0.12.26->llama-index->tinytroupe==0.4.0)
  Downloading mypy_extensions-1.0.0-py3-none-any.whl.metadata (1.1 kB)
Collecting pysocks!=1.5.7,<2.0,>=1.5.6 (from urllib3[socks]<3,>=1.26->selenium<5.0.0,>=4.17.2->llama-index-readers-web->tinytroupe==0.4.0)
  Downloading PySocks-1.7.1-py3-none-any.whl.metadata (13 kB)
Collecting marshmallow<4.0.0,>=3.18.0 (from dataclasses-json->llama-index-core<0.13.0,>=0.12.26->llama-index->tinytroupe==0.4.0)
  Downloading marshmallow-3.26.1-py3-none-any.whl.metadata (7.3 kB)
Requirement already satisfied: threadpoolctl>=3.1.0 in /home/codespace/.local/lib/python3.12/site-packages (from scikit-learn->sentence-transformers>=2.6.1->llama-index-embeddings-huggingface->tinytroupe==0.4.0) (3.6.0)
Requirement already satisfied: argon2-cffi-bindings in /home/codespace/.local/lib/python3.12/site-packages (from argon2-cffi>=21.1->jupyter-server<3,>=2.4.0->jupyterlab->jupyter->tinytroupe==0.4.0) (21.2.0)
Requirement already satisfied: parso<0.9.0,>=0.8.4 in /home/codespace/.local/lib/python3.12/site-packages (from jedi>=0.16->ipython>=7.23.1->ipykernel->jupyter->tinytroupe==0.4.0) (0.8.4)
Requirement already satisfied: jsonschema-specifications>=2023.03.6 in /home/codespace/.local/lib/python3.12/site-packages (from jsonschema>=4.18.0->jupyterlab-server<3,>=2.27.1->jupyterlab->jupyter->tinytroupe==0.4.0) (2024.10.1)
Requirement already satisfied: referencing>=0.28.4 in /home/codespace/.local/lib/python3.12/site-packages (from jsonschema>=4.18.0->jupyterlab-server<3,>=2.27.1->jupyterlab->jupyter->tinytroupe==0.4.0) (0.36.2)
Requirement already satisfied: rpds-py>=0.7.1 in /home/codespace/.local/lib/python3.12/site-packages (from jsonschema>=4.18.0->jupyterlab-server<3,>=2.27.1->jupyterlab->jupyter->tinytroupe==0.4.0) (0.23.1)
Requirement already satisfied: python-json-logger>=2.0.4 in /home/codespace/.local/lib/python3.12/site-packages (from jupyter-events>=0.11.0->jupyter-server<3,>=2.4.0->jupyterlab->jupyter->tinytroupe==0.4.0) (3.3.0)
Requirement already satisfied: rfc3339-validator in /home/codespace/.local/lib/python3.12/site-packages (from jupyter-events>=0.11.0->jupyter-server<3,>=2.4.0->jupyterlab->jupyter->tinytroupe==0.4.0) (0.1.4)
Requirement already satisfied: rfc3986-validator>=0.1.1 in /home/codespace/.local/lib/python3.12/site-packages (from jupyter-events>=0.11.0->jupyter-server<3,>=2.4.0->jupyterlab->jupyter->tinytroupe==0.4.0) (0.1.1)
Collecting platformdirs>=2.5 (from jupyter-core!=5.0.*,>=4.12->ipykernel->jupyter->tinytroupe==0.4.0)
  Downloading platformdirs-4.3.7-py3-none-any.whl.metadata (11 kB)
Collecting python-dotenv<2.0.0,>=1.0.1 (from llama-cloud-services>=0.6.4->llama-parse>=0.5.0->llama-index-readers-llama-parse>=0.4.0->llama-index->tinytroupe==0.4.0)
  Downloading python_dotenv-1.1.0-py3-none-any.whl.metadata (24 kB)
Requirement already satisfied: ptyprocess>=0.5 in /home/codespace/.local/lib/python3.12/site-packages (from pexpect>4.3->ipython>=7.23.1->ipykernel->jupyter->tinytroupe==0.4.0) (0.7.0)
Requirement already satisfied: colorama>=0.4 in /home/codespace/.local/lib/python3.12/site-packages (from griffe->banks<3.0.0,>=2.0.0->llama-index-core<0.13.0,>=0.12.26->llama-index->tinytroupe==0.4.0) (0.4.6)
Requirement already satisfied: executing>=1.2.0 in /home/codespace/.local/lib/python3.12/site-packages (from stack_data->ipython>=7.23.1->ipykernel->jupyter->tinytroupe==0.4.0) (2.2.0)
Requirement already satisfied: asttokens>=2.1.0 in /home/codespace/.local/lib/python3.12/site-packages (from stack_data->ipython>=7.23.1->ipykernel->jupyter->tinytroupe==0.4.0) (3.0.0)
Requirement already satisfied: pure-eval in /home/codespace/.local/lib/python3.12/site-packages (from stack_data->ipython>=7.23.1->ipykernel->jupyter->tinytroupe==0.4.0) (0.2.3)
Requirement already satisfied: fqdn in /home/codespace/.local/lib/python3.12/site-packages (from jsonschema[format-nongpl]>=4.18.0->jupyter-events>=0.11.0->jupyter-server<3,>=2.4.0->jupyterlab->jupyter->tinytroupe==0.4.0) (1.5.1)
Requirement already satisfied: isoduration in /home/codespace/.local/lib/python3.12/site-packages (from jsonschema[format-nongpl]>=4.18.0->jupyter-events>=0.11.0->jupyter-server<3,>=2.4.0->jupyterlab->jupyter->tinytroupe==0.4.0) (20.11.0)
Requirement already satisfied: jsonpointer>1.13 in /home/codespace/.local/lib/python3.12/site-packages (from jsonschema[format-nongpl]>=4.18.0->jupyter-events>=0.11.0->jupyter-server<3,>=2.4.0->jupyterlab->jupyter->tinytroupe==0.4.0) (3.0.0)
Requirement already satisfied: uri-template in /home/codespace/.local/lib/python3.12/site-packages (from jsonschema[format-nongpl]>=4.18.0->jupyter-events>=0.11.0->jupyter-server<3,>=2.4.0->jupyterlab->jupyter->tinytroupe==0.4.0) (1.3.0)
Requirement already satisfied: webcolors>=24.6.0 in /home/codespace/.local/lib/python3.12/site-packages (from jsonschema[format-nongpl]>=4.18.0->jupyter-events>=0.11.0->jupyter-server<3,>=2.4.0->jupyterlab->jupyter->tinytroupe==0.4.0) (24.11.1)
Requirement already satisfied: arrow>=0.15.0 in /home/codespace/.local/lib/python3.12/site-packages (from isoduration->jsonschema[format-nongpl]>=4.18.0->jupyter-events>=0.11.0->jupyter-server<3,>=2.4.0->jupyterlab->jupyter->tinytroupe==0.4.0) (1.3.0)
Requirement already satisfied: types-python-dateutil>=2.8.10 in /home/codespace/.local/lib/python3.12/site-packages (from arrow>=0.15.0->isoduration->jsonschema[format-nongpl]>=4.18.0->jupyter-events>=0.11.0->jupyter-server<3,>=2.4.0->jupyterlab->jupyter->tinytroupe==0.4.0) (2.9.0.20241206)
Downloading openai-1.69.0-py3-none-any.whl (599 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 599.1/599.1 kB 22.5 MB/s eta 0:00:00
Downloading pydantic-2.11.1-py3-none-any.whl (442 kB)
Downloading pydantic_core-2.33.0-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (2.0 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.0/2.0 MB 43.6 MB/s eta 0:00:00
Downloading chevron-0.14.0-py3-none-any.whl (11 kB)
Downloading jupyter-1.1.1-py2.py3-none-any.whl (2.7 kB)
Downloading llama_index-0.12.26-py3-none-any.whl (7.0 kB)
Downloading llama_index_embeddings_azure_openai-0.3.2-py3-none-any.whl (4.4 kB)
Downloading llama_index_embeddings_huggingface-0.5.2-py3-none-any.whl (8.9 kB)
Downloading llama_index_readers_web-0.3.8-py3-none-any.whl (97 kB)
Downloading Markdown-3.7-py3-none-any.whl (106 kB)
Downloading msal-1.32.0-py3-none-any.whl (114 kB)
Downloading pypandoc-1.15-py3-none-any.whl (21 kB)
Downloading pytest-8.3.5-py3-none-any.whl (343 kB)
Downloading pytest_cov-6.0.0-py3-none-any.whl (22 kB)
Downloading rich-13.9.4-py3-none-any.whl (242 kB)
Downloading tiktoken-0.9.0-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (1.2 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.2/1.2 MB 38.3 MB/s eta 0:00:00
Downloading aiohttp-3.11.14-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (1.7 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.7/1.7 MB 45.3 MB/s eta 0:00:00
Downloading annotated_types-0.7.0-py3-none-any.whl (13 kB)
Downloading chromedriver_autoinstaller-0.6.4-py3-none-any.whl (7.6 kB)
Downloading coverage-7.7.1-cp312-cp312-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl (244 kB)
Using cached cryptography-44.0.2-cp39-abi3-manylinux_2_28_x86_64.whl (4.2 MB)
Downloading distro-1.9.0-py3-none-any.whl (20 kB)
Downloading huggingface_hub-0.29.3-py3-none-any.whl (468 kB)
Downloading jiter-0.9.0-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (351 kB)
Downloading llama_index_agent_openai-0.4.6-py3-none-any.whl (13 kB)
Downloading llama_index_cli-0.4.1-py3-none-any.whl (28 kB)
Downloading llama_index_core-0.12.27-py3-none-any.whl (1.6 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.6/1.6 MB 44.9 MB/s eta 0:00:00
Downloading llama_index_embeddings_openai-0.3.1-py3-none-any.whl (6.2 kB)
Downloading llama_index_indices_managed_llama_cloud-0.6.9-py3-none-any.whl (14 kB)
Downloading llama_index_llms_azure_openai-0.3.2-py3-none-any.whl (7.3 kB)
Downloading llama_index_llms_openai-0.3.29-py3-none-any.whl (23 kB)
Downloading llama_index_multi_modal_llms_openai-0.4.3-py3-none-any.whl (5.9 kB)
Downloading llama_index_program_openai-0.3.1-py3-none-any.whl (5.3 kB)
Downloading llama_index_question_gen_openai-0.3.0-py3-none-any.whl (2.9 kB)
Downloading llama_index_readers_file-0.4.7-py3-none-any.whl (40 kB)
Downloading llama_index_readers_llama_parse-0.4.0-py3-none-any.whl (2.5 kB)
Downloading markdown_it_py-3.0.0-py3-none-any.whl (87 kB)
Downloading newspaper3k-0.2.8-py3-none-any.whl (211 kB)
Downloading lxml-5.3.1-cp312-cp312-manylinux_2_28_x86_64.whl (5.0 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 5.0/5.0 MB 50.3 MB/s eta 0:00:00
Downloading nltk-3.9.1-py3-none-any.whl (1.5 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.5/1.5 MB 29.6 MB/s eta 0:00:00
Downloading playwright-1.51.0-py3-none-manylinux1_x86_64.whl (45.2 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 45.2/45.2 MB 53.8 MB/s eta 0:00:00
Downloading pluggy-1.5.0-py3-none-any.whl (20 kB)
Downloading PyJWT-2.10.1-py3-none-any.whl (22 kB)
Downloading regex-2024.11.6-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (796 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 796.9/796.9 kB 29.4 MB/s eta 0:00:00
Downloading selenium-4.30.0-py3-none-any.whl (9.4 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 9.4/9.4 MB 55.7 MB/s eta 0:00:00
Downloading sentence_transformers-4.0.1-py3-none-any.whl (340 kB)
Downloading tqdm-4.67.1-py3-none-any.whl (78 kB)
Downloading typing_inspection-0.4.0-py3-none-any.whl (14 kB)
Downloading iniconfig-2.1.0-py3-none-any.whl (6.0 kB)
Downloading ipywidgets-8.1.5-py3-none-any.whl (139 kB)
Downloading jupyter_console-6.6.3-py3-none-any.whl (24 kB)
Downloading notebook-7.3.3-py3-none-any.whl (13.1 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 13.1/13.1 MB 54.8 MB/s eta 0:00:00
Downloading aiohappyeyeballs-2.6.1-py3-none-any.whl (15 kB)
Downloading aiosignal-1.3.2-py2.py3-none-any.whl (7.6 kB)
Downloading azure_identity-1.21.0-py3-none-any.whl (189 kB)
Downloading banks-2.1.0-py3-none-any.whl (28 kB)
Downloading cssselect-1.3.0-py3-none-any.whl (18 kB)
Downloading Deprecated-1.2.18-py2.py3-none-any.whl (10.0 kB)
Downloading dirtyjson-1.0.8-py3-none-any.whl (25 kB)
Downloading feedparser-6.0.11-py3-none-any.whl (81 kB)
Downloading filetype-1.2.0-py2.py3-none-any.whl (19 kB)
Downloading frozenlist-1.5.0-cp312-cp312-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl (283 kB)
Downloading greenlet-3.1.1-cp312-cp312-manylinux_2_24_x86_64.manylinux_2_28_x86_64.whl (613 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 613.1/613.1 kB 24.6 MB/s eta 0:00:00
Downloading jupyterlab_widgets-3.0.13-py3-none-any.whl (214 kB)
Downloading llama_cloud-0.1.17-py3-none-any.whl (253 kB)
Downloading llama_parse-0.6.4.post1-py3-none-any.whl (4.9 kB)
Downloading mdurl-0.1.2-py3-none-any.whl (10.0 kB)
Downloading multidict-6.2.0-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (132 kB)
Downloading propcache-0.3.1-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (245 kB)
Downloading pyee-12.1.1-py3-none-any.whl (15 kB)
Downloading pypdf-5.4.0-py3-none-any.whl (302 kB)
Downloading sqlalchemy-2.0.40-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (3.3 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 3.3/3.3 MB 52.6 MB/s eta 0:00:00
Downloading striprtf-0.0.26-py3-none-any.whl (6.9 kB)
Downloading tenacity-9.0.0-py3-none-any.whl (28 kB)
Downloading tldextract-5.1.3-py3-none-any.whl (104 kB)
Downloading transformers-4.50.3-py3-none-any.whl (10.2 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 10.2/10.2 MB 64.9 MB/s eta 0:00:00
Downloading trio-0.29.0-py3-none-any.whl (492 kB)
Downloading trio_websocket-0.12.2-py3-none-any.whl (21 kB)
Downloading typing_inspect-0.9.0-py3-none-any.whl (8.8 kB)
Downloading widgetsnbextension-4.0.13-py3-none-any.whl (2.3 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.3/2.3 MB 46.1 MB/s eta 0:00:00
Downloading wrapt-1.17.2-cp312-cp312-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl (89 kB)
Downloading yarl-1.18.3-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (336 kB)
Downloading click-8.1.8-py3-none-any.whl (98 kB)
Downloading dataclasses_json-0.6.7-py3-none-any.whl (28 kB)
Downloading azure_core-1.32.0-py3-none-any.whl (198 kB)
Downloading llama_cloud_services-0.6.9-py3-none-any.whl (29 kB)
Downloading marshmallow-3.26.1-py3-none-any.whl (50 kB)
Downloading msal_extensions-1.3.1-py3-none-any.whl (20 kB)
Downloading mypy_extensions-1.0.0-py3-none-any.whl (4.7 kB)
Downloading outcome-1.3.0.post0-py2.py3-none-any.whl (10 kB)
Downloading platformdirs-4.3.7-py3-none-any.whl (18 kB)
Downloading PySocks-1.7.1-py3-none-any.whl (16 kB)
Downloading requests_file-2.1.0-py2.py3-none-any.whl (4.2 kB)
Downloading safetensors-0.5.3-cp38-abi3-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (471 kB)
Downloading tokenizers-0.21.1-cp39-abi3-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (3.0 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 3.0/3.0 MB 51.1 MB/s eta 0:00:00
Downloading wsproto-1.2.0-py3-none-any.whl (24 kB)
Downloading griffe-1.7.1-py3-none-any.whl (129 kB)
Downloading sortedcontainers-2.4.0-py2.py3-none-any.whl (29 kB)
Downloading python_dotenv-1.1.0-py3-none-any.whl (20 kB)
Building wheels for collected packages: tinytroupe, docx, html2text, tinysegmenter, spider-client, feedfinder2, jieba3k, sgmllib3k
  Building wheel for tinytroupe (pyproject.toml) ... done
  Created wheel for tinytroupe: filename=tinytroupe-0.4.0-py3-none-any.whl size=154714 sha256=135f2fac1f7d52c9e1aae3cee982ab9ee8d7b8d4b735c9604e1daeed9416825b
  Stored in directory: /tmp/pip-ephem-wheel-cache-ufj1t5sy/wheels/af/11/ad/9951d4c710bec90b06a3d3bffc01318508af389dcbb200b53f
  Building wheel for docx (pyproject.toml) ... done
  Created wheel for docx: filename=docx-0.2.4-py3-none-any.whl size=53931 sha256=45e151543d1d46f13216ace8a3361084e0ed208d6684abc9814d547e269712fc
  Stored in directory: /home/codespace/.cache/pip/wheels/f3/ba/dd/43ed5f165600f41deddeb1e382c56ffc1067c09ec5bd705f39
  Building wheel for html2text (pyproject.toml) ... done
  Created wheel for html2text: filename=html2text-2024.2.26-py3-none-any.whl size=33169 sha256=7d5227efc33aae6d87efbc861a1e0e26751ef31c425170e7bc06b10752c6379d
  Stored in directory: /home/codespace/.cache/pip/wheels/2b/01/23/578505d65e2a97d78bf1fe3fc8256ecf37572dc1df598b0eaf
  Building wheel for tinysegmenter (pyproject.toml) ... done
  Created wheel for tinysegmenter: filename=tinysegmenter-0.3-py3-none-any.whl size=13634 sha256=b37e1162355c536077002fc98e75a0db9123ec30584c08f2651e44af8294c488
  Stored in directory: /home/codespace/.cache/pip/wheels/a5/91/9f/00d66475960891a64867914273fcaf78df6cb04d905b104a2a
  Building wheel for spider-client (pyproject.toml) ... done
  Created wheel for spider-client: filename=spider_client-0.0.27-py3-none-any.whl size=6053 sha256=8b501018e33e6fa56fde34f3b5fe75d124841d06c9f663415888935ca44c1f67
  Stored in directory: /home/codespace/.cache/pip/wheels/6c/41/42/4155300999390be7e455a6b05c602849f5810bf9383c43adb2
  Building wheel for feedfinder2 (pyproject.toml) ... done
  Created wheel for feedfinder2: filename=feedfinder2-0.0.4-py3-none-any.whl size=3393 sha256=1cd546afbe5f7304ff12d9ff214e399fef95e5014801e516c20e5a05cf251cbe
  Stored in directory: /home/codespace/.cache/pip/wheels/9f/9f/fb/364871d7426d3cdd4d293dcf7e53d97f160c508b2ccf00cc79
  Building wheel for jieba3k (pyproject.toml) ... done
  Created wheel for jieba3k: filename=jieba3k-0.35.1-py3-none-any.whl size=7398403 sha256=6fda088a0110cab3c2346f2881be03b0d845a207928335ba4f3c179e4f4bd611
  Stored in directory: /home/codespace/.cache/pip/wheels/26/72/f7/fff392a8d4ea988dea4ccf9788599d09462a7f5e51e04f8a92
  Building wheel for sgmllib3k (pyproject.toml) ... done
  Created wheel for sgmllib3k: filename=sgmllib3k-1.0.0-py3-none-any.whl size=6091 sha256=453275045d585c4d3eb1765980e51d0d7b0c036adc741e7a401148aa3e492666
  Stored in directory: /home/codespace/.cache/pip/wheels/03/f5/1a/23761066dac1d0e8e683e5fdb27e12de53209d05a4a37e6246
Successfully built tinytroupe docx html2text tinysegmenter spider-client feedfinder2 jieba3k sgmllib3k
Installing collected packages: tinysegmenter, striprtf, sortedcontainers, sgmllib3k, jieba3k, filetype, dirtyjson, chevron, wsproto, wrapt, widgetsnbextension, typing-inspection, tqdm, tenacity, safetensors, regex, python-dotenv, pysocks, pypdf, pypandoc, PyJWT, pyee, pydantic-core, propcache, pluggy, platformdirs, outcome, mypy-extensions, multidict, mdurl, marshmallow, markdown, lxml, jupyterlab-widgets, jiter, iniconfig, html2text, griffe, greenlet, frozenlist, feedparser, distro, cssselect, coverage, click, chromedriver-autoinstaller, annotated-types, aiohappyeyeballs, yarl, typing-inspect, trio, tiktoken, SQLAlchemy, spider-client, requests-file, pytest, pydantic, playwright, nltk, markdown-it-py, huggingface-hub, feedfinder2, docx, deprecated, cryptography, azure-core, aiosignal, trio-websocket, tokenizers, tldextract, rich, pytest-cov, openai, llama-cloud, ipywidgets, dataclasses-json, banks, aiohttp, transformers, selenium, newspaper3k, msal, llama-index-core, sentence-transformers, msal-extensions, llama-index-readers-web, llama-index-readers-file, llama-index-llms-openai, llama-index-indices-managed-llama-cloud, llama-index-embeddings-openai, llama-cloud-services, jupyter-console, llama-parse, llama-index-multi-modal-llms-openai, llama-index-embeddings-huggingface, llama-index-cli, llama-index-agent-openai, azure-identity, llama-index-readers-llama-parse, llama-index-program-openai, llama-index-llms-azure-openai, llama-index-question-gen-openai, llama-index-embeddings-azure-openai, llama-index, notebook, jupyter, tinytroupe
  Attempting uninstall: platformdirs
    Found existing installation: platformdirs 4.3.6
    Uninstalling platformdirs-4.3.6:
      Successfully uninstalled platformdirs-4.3.6
Successfully installed PyJWT-2.10.1 SQLAlchemy-2.0.40 aiohappyeyeballs-2.6.1 aiohttp-3.11.14 aiosignal-1.3.2 annotated-types-0.7.0 azure-core-1.32.0 azure-identity-1.21.0 banks-2.1.0 chevron-0.14.0 chromedriver-autoinstaller-0.6.4 click-8.1.8 coverage-7.7.1 cryptography-44.0.2 cssselect-1.3.0 dataclasses-json-0.6.7 deprecated-1.2.18 dirtyjson-1.0.8 distro-1.9.0 docx-0.2.4 feedfinder2-0.0.4 feedparser-6.0.11 filetype-1.2.0 frozenlist-1.5.0 greenlet-3.1.1 griffe-1.7.1 html2text-2024.2.26 huggingface-hub-0.29.3 iniconfig-2.1.0 ipywidgets-8.1.5 jieba3k-0.35.1 jiter-0.9.0 jupyter-1.1.1 jupyter-console-6.6.3 jupyterlab-widgets-3.0.13 llama-cloud-0.1.17 llama-cloud-services-0.6.9 llama-index-0.12.26 llama-index-agent-openai-0.4.6 llama-index-cli-0.4.1 llama-index-core-0.12.27 llama-index-embeddings-azure-openai-0.3.2 llama-index-embeddings-huggingface-0.5.2 llama-index-embeddings-openai-0.3.1 llama-index-indices-managed-llama-cloud-0.6.9 llama-index-llms-azure-openai-0.3.2 llama-index-llms-openai-0.3.29 llama-index-multi-modal-llms-openai-0.4.3 llama-index-program-openai-0.3.1 llama-index-question-gen-openai-0.3.0 llama-index-readers-file-0.4.7 llama-index-readers-llama-parse-0.4.0 llama-index-readers-web-0.3.8 llama-parse-0.6.4.post1 lxml-5.3.1 markdown-3.7 markdown-it-py-3.0.0 marshmallow-3.26.1 mdurl-0.1.2 msal-1.32.0 msal-extensions-1.3.1 multidict-6.2.0 mypy-extensions-1.0.0 newspaper3k-0.2.8 nltk-3.9.1 notebook-7.3.3 openai-1.69.0 outcome-1.3.0.post0 platformdirs-4.3.7 playwright-1.51.0 pluggy-1.5.0 propcache-0.3.1 pydantic-2.11.1 pydantic-core-2.33.0 pyee-12.1.1 pypandoc-1.15 pypdf-5.4.0 pysocks-1.7.1 pytest-8.3.5 pytest-cov-6.0.0 python-dotenv-1.1.0 regex-2024.11.6 requests-file-2.1.0 rich-13.9.4 safetensors-0.5.3 selenium-4.30.0 sentence-transformers-4.0.1 sgmllib3k-1.0.0 sortedcontainers-2.4.0 spider-client-0.0.27 striprtf-0.0.26 tenacity-9.0.0 tiktoken-0.9.0 tinysegmenter-0.3 tinytroupe-0.4.0 tldextract-5.1.3 tokenizers-0.21.1 tqdm-4.67.1 transformers-4.50.3 trio-0.29.0 trio-websocket-0.12.2 typing-inspect-0.9.0 typing-inspection-0.4.0 widgetsnbextension-4.0.13 wrapt-1.17.2 wsproto-1.2.0 yarl-1.18.3
@ShivaniPolaboyna0520 ➜ /workspaces/tinytroupe5/TinyTroupe (main) $ export OPENAI_API_KEY="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"
@ShivaniPolaboyna0520 ➜ /workspaces/tinytroupe5/TinyTroupe (main) $ python
Python 3.12.1 (main, Mar 17 2025, 17:13:06) [GCC 9.4.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> from tinytroupe.examples import create_lisa_the_data_scientist
Looking for default config on: /workspaces/tinytroupe5/TinyTroupe/tinytroupe/utils/../config.ini
Failed to find custom config on: /workspaces/tinytroupe5/TinyTroupe/config.ini
Will use only default values. IF THINGS FAIL, TRY CUSTOMIZING MODEL, API TYPE, etc.

!!!!
DISCLAIMER: TinyTroupe relies on Artificial Intelligence (AI) models to generate content. 
The AI models are not perfect and may produce inappropriate or inacurate results. 
For any serious or consequential use, please review the generated content before using it.
!!!!


=================================
Current TinyTroupe configuration 
=================================
[OpenAI]
api_type = openai
azure_api_version = 2023-05-15
model = gpt-4o-mini
max_tokens = 4000
temperature = 1.2
freq_penalty = 0.0
presence_penalty = 0.0
timeout = 60
max_attempts = 5
waiting_time = 1
exponential_backoff_factor = 5
embedding_model = text-embedding-3-small
cache_api_calls = False
cache_file_name = openai_api_cache.pickle
max_content_display_length = 1024

[Simulation]
rai_harmful_content_prevention = True
rai_copyright_infringement_prevention = True

[Logging]
loglevel = ERROR

>>> lisa = create_lisa_the_data_scientist()
>>> lisa
TinyPerson(name='Lisa Carter')
>>> lisa.listen_and_act("Tell me about your life.")
USER --> Lisa Carter: [CONVERSATION] 
          > Tell me about your life.
Lisa Carter acts: [THINK] 
                 > I need to share about my life, including my background, education, and current
                 > job. I should also mention my interests and hobbies to give a well-rounded view.
Lisa Carter acts: [TALK] 
                 > Sure! I grew up in Vancouver, Canada, in a tech-savvy family. My parents were
                 > software engineers, which inspired my interest in technology from a young age. I
                 > pursued a Master's in Data Science at the University of Toronto, where I focused
                 > on improving search relevance using context-aware models. Now, I work as a Data
                 > Scientist at Microsoft in the M365 Search team, analyzing user behavior to
                 > enhance search results. I love learning about AI and machine learning, and in my
                 > free time, I enjoy cooking, playing the piano, and watching movies.
Lisa Carter acts: [DONE] 

>>> from tinytroupe.agent import TinyPerson
>>> shivani = TinyPerson("Shivani")
>>> shivani.define("age", 24)
>>> shivani.define("nationality", "Indian")
>>> shivani.define("occupation", {
...                 "title": "student",
...                 "organization": "pace unieristy",
...                 "description":
...                 """
...                 You are a student. You study  at pace university, in the masters in data science . Your main goal is to analyze 
...                 user behavior and feedback data, and use it to improve the relevance and quality of the search results. 
...                 You also build and test machine learning models for various search scenarios, such as natural language 
...                 understanding, query expansion, and ranking. You care a lot about making sure your data analysis and 
...                 models are accurate, reliable and scalable. Your main difficulties typically involve dealing with noisy, 
...                 incomplete or biased data, and finding the best ways to communicate your findings and recommendations to 
...                 other teams. You are also responsible for making sure your data and models are compliant with privacy and 
...                 security policies.
...                 """})
>>>   shivani.define("behaviors", {"routines": ["Every morning, you wake up, do some yoga, and check your emails."]})
  File "<stdin>", line 1
    shivani.define("behaviors", {"routines": ["Every morning, you wake up, do some yoga, and check your emails."]})
IndentationError: unexpected indent
>>> shivani.define("behaviors", {"routines": ["Every morning, you wake up, do some yoga, and check your emails."]})
>>> 
>>> shivani.define("personality", 
...                         {"traits": [
...                             "You are curious and love to learn new things.",
...                             "You are analytical and like to solve problems.",
...                             "You are friendly and enjoy working with others.",
...                             "You don't give up easily, and always try to find a solution. However, sometimes you can get frustrated when things don't work as expected."
...                       ]})
>>> shivani.define("preferences", 
...                       {"interests": [
...                           "Artificial intelligence and machine learning.",
...                           "Natural language processing and conversational agents.",
...                           "Search engine optimization and user experience.",
...                           "Cooking and trying new recipes.",
...                           "Playing the badminton.",
...                           "Watching movies, especially comedies and thrillers."
...                         ]})
>>> 
>>> shivani.listen_and_act("what is software engineer?")
USER --> Shivani: [CONVERSATION] 
          > what is software engineer?
Shivani acts: [THINK] 
             > A software engineer is someone who applies principles of software engineering to
             > design, develop, maintain, test, and evaluate computer software. They work on various
             > aspects of software development, including coding, debugging, and collaborating with
             > other team members to create effective software solutions.
Shivani acts: [TALK] 
             > A software engineer is someone who designs and develops software applications. They
             > use programming languages and tools to create software that meets user needs. Would
             > you like to know more about what they do or the skills required?
Shivani acts: [DONE] 

>>> shivani.listen_and_act("Tell me about singing")
USER --> Shivani: [CONVERSATION] 
          > Tell me about singing
Shivani acts: [THINK] 
             > Singing is the act of producing musical sounds with the voice. It involves using the
             > vocal cords to create melodies and harmonies, often accompanied by lyrics. People
             > sing for various reasons, including entertainment, expression of emotions, and
             > cultural traditions. I wonder if the person wants to know about techniques or styles
             > of singing.
Shivani acts: [TALK] 
             > Singing is a beautiful form of expression that allows people to convey emotions and
             > tell stories through music. It can be done solo or in groups, and there are many
             > styles, such as classical, pop, and jazz. Do you have a specific aspect of singing
             > you want to know more about?
Shivani acts: [DONE] 

>>> from tinytroupe.enivronment import TinyWorld
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
ModuleNotFoundError: No module named 'tinytroupe.enivronment'
>>> from tinytroupe.environment import TinyWorld
>>> shivani = TinyPerson("shivani")
>>> sama = TinyPerson("sama")
>>> jon.define("age", 45)  # 📝 Adjust the age to fit the scenario
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'jon' is not defined
>>> jon.define("age", 45)  # 📝 Adjust the age to fit the scenario
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'jon' is not defined
>>> sama.define("age", 50) 
>>>    jon.define("nationality", "American")
  File "<stdin>", line 1
    jon.define("nationality", "American")
IndentationError: unexpected indent
>>> sama.define("nationality", "Japanese")
>>> sama.define("occupation", "beggar")
>>> sama.define("professional_history","""Experienced in street fundraising, effectively engaging with the public to solicit donations. Skilled in resource management, optimizing earnings in high-traffic areas. Strong interpersonal abilities, building rapport through storytelling and emotional appeal. Adaptable to unpredictable challenges, demonstrating resilience in adverse conditions. Efficient in financial planning to prioritize essential needs.""")
>>> chris = TinyPerson("Chris")
>>> 
>>> # Define basic attributes
>>> chris.define("age", 50)  # 📝 Adjust the age to fit the scenario
>>> chris.define("nationality", "American")
>>> chris.define("occupation", "Congressman in Charge of Approving Funding Proposals")
>>> 
>>> # Define professional history and routine
>>> chris.define("professional_history", """
... Chris has served as a Congressman for over 15 years, representing a diverse constituency.
... As part of his duties, he oversees the evaluation and approval of government funding proposals,
... including those aimed at social initiatives like homeless shelters.
... Chris has a reputation for being pragmatic and data-driven in his decision-making.
... """)
>>> world = TinyWorld("Conference Room 1", [sama,chris])
>>> world.run(3)
──────────────────────────────────────────────────────────────── Conference Room 1 step 1 of 3 ─────────────────────────────────────────────────────────────────
sama acts: [DONE] 

Chris acts: [DONE] 

──────────────────────────────────────────────────────────────── Conference Room 1 step 2 of 3 ─────────────────────────────────────────────────────────────────
sama acts: [DONE] 

Chris acts: [DONE] 

──────────────────────────────────────────────────────────────── Conference Room 1 step 3 of 3 ─────────────────────────────────────────────────────────────────
sama acts: [DONE] 

Chris acts: [DONE] 

>>> sama.listen("You want to ask chris for funding opportunities.")
USER --> sama: [CONVERSATION] 
          > You want to ask chris for funding opportunities.
TinyPerson(name='sama')
>>> world.run(3)
──────────────────────────────────────────────────────────────── Conference Room 1 step 1 of 3 ─────────────────────────────────────────────────────────────────
sama acts: [REACH_OUT] 

sama acts: [DONE] 

Conference Room 1 --> sama: [SOCIAL] 
                       > Chris was successfully reached out, and is now available for interaction.
Conference Room 1 --> Chris: [SOCIAL] 
                       > sama reached out to you, and is now available for interaction.
Chris acts: [REACH_OUT] 

Chris acts: [TALK] 
           > Hi sama, thanks for reaching out! How can I assist you today?
Chris acts: [DONE] 

Conference Room 1 --> Chris: [SOCIAL] 
                       > sama was successfully reached out, and is now available for interaction.
Conference Room 1 --> sama: [SOCIAL] 
                       > Chris reached out to you, and is now available for interaction.
Chris --> sama: [CONVERSATION] 
           > Hi sama, thanks for reaching out! How can I assist you today?
──────────────────────────────────────────────────────────────── Conference Room 1 step 2 of 3 ─────────────────────────────────────────────────────────────────
sama acts: [THINK] 
          > Chris seems friendly and open to helping. I should clearly explain what I need regarding
          > funding opportunities.
sama acts: [TALK] 
          > Hi Chris! Thank you for getting back to me. I wanted to ask if there are any funding
          > opportunities available that I could apply for.
sama acts: [DONE] 

sama --> Chris: [CONVERSATION] 
          > Hi Chris! Thank you for getting back to me. I wanted to ask if there are any funding
          > opportunities available that I could apply for.
Chris acts: [THINK] 
           > Sama is asking about funding opportunities. I need to recall the current funding
           > proposals and see if any are applicable for sama.
Chris acts: [TALK] 
           > Currently, there are several funding opportunities available, particularly for social
           > initiatives. Can you tell me more about what specific area you're interested in?
Chris acts: [DONE] 

Chris --> sama: [CONVERSATION] 
           > Currently, there are several funding opportunities available, particularly for social
           > initiatives. Can you tell me more about what specific area you're interested in?
──────────────────────────────────────────────────────────────── Conference Room 1 step 3 of 3 ─────────────────────────────────────────────────────────────────
sama acts: [THINK] 
          > Chris mentioned there are several funding opportunities for social initiatives. I need
          > to clarify my specific area of interest to get the most relevant information.
sama acts: [TALK] 
          > I'm particularly interested in funding for community outreach programs. Do you have any
          > specific opportunities that align with that?
sama acts: [DONE] 

sama --> Chris: [CONVERSATION] 
          > I'm particularly interested in funding for community outreach programs. Do you have any
          > specific opportunities that align with that?
Chris acts: [THINK] 
           > Sama is interested in funding for community outreach programs. I need to recall any
           > specific funding proposals that might fit this description.
Chris acts: [TALK] 
           > Yes, we do have some funding opportunities specifically for community outreach
           > programs. One of the proposals focuses on enhancing local engagement and support for
           > underserved populations. Would you like more details on that?
Chris acts: [DONE] 

Chris --> sama: [CONVERSATION] 
           > Yes, we do have some funding opportunities specifically for community outreach
           > programs. One of the proposals focuses on enhancing local engagement and support for
           > underserved populations. Would you like more details on that?
>>> 
