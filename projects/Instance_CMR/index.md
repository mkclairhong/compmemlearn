In retrieved context accounts of memory search like the Context Maintenance and Retrieval (CMR) model [@polyn2009context], representations of studied items in a free recall experiment are associated with states of an internal representation of temporal context that slowly evolves across the study period. 
These mechanisms enable models to account for organizational effects in recall sequences, such as the tendency for related items to be recalled successively. 
Retrieved context models tend to specify these dynamics in terms of a simplified neural network, as building a single prototypical pattern of associations between each item and context (and vice versa) across experience. 
By contrast, models of categorization and other memory phenomena have increasingly converged on instance-based architectures [@hintzman1984minerva] that conceptualize memory as a stack of trace vectors that each represent discrete experiences and support recall through parallel, nonlinear activation based on similarity to a probe. 
To investigate the consequences of this distinction we present an instance-based specification of CMR that encodes associations between studied items and context by instantiating memory traces corresponding to each experience, and drives recall through context-based coactivation of those traces. 
We analyze the model's ability to account for traditional phenomena that have been used as support for the original prototypical specification of CMR, evaluate conditions under which the specifications might behave differently, and explore the model's capacity for integration with existing instance-based models to elucidate a broader collection of memory phenomena.