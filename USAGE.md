

```bash
pip install -e .
```

```python
from crisper_api_client import AuthenticatedClient
from crisper_api_client.api.api import api_v1_source_list

token = "<add-token-here>"
client = AuthenticatedClient(base_url="https://api.crisper.ai", token=token)
api_v1_assistant_list.sync_detailed(client=client)
```


### sdk.py usage
```python
from crisper_api_client import Crisper
c = Crisper()
x = c.create_assistant(name="slfdj")
x.add_knowledge_source(content_type="text", text="hello world. this is apoorv")

# TODO:
x.ask
```
