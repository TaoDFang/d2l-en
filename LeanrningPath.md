1. Introduction , read

2. Preliminaries , read

3. Linear Nueral networks for classification
    3.1 linear regression, go through: yes, exercise: no

    3.2 Object-Oriented Design for Implementation, go through: yes , exercise:  no
    """
    on a high level
    we wish to have three classes: 
    (i) `Module` contains models, losses, and optimization methods; 
    (ii) `DataModule` provides data loaders for training and validation; 
    (iii) both classes are combined using the `Trainer` class, which allows us to
    train models on a variety of hardware platforms.  
    """

    3.3 Synthetic Regression Data, go through: yes  , exercise:no  

    3.4 Linear Regression Implementation from Scratch , go through: , exercise: 
    (implementing things from scratch is the only way to make sure that you really know what you are doing)

    3.5 Concise Implementation of Linear Regression, go through: , exercise: 
    build linear regression model with pytorch framework, could be the quick entry to pytoch  world 

    3.6, go through: , exercise: 

    3.7, go through: , exercise: 


...

6. Builders' guide 
    6.1 Layers and Modules  , go through: , exercise: 
    """
    From a programming standpoint, a module is represented by a *class*.
    Any subclass of it must define a forward propagation method
    that transforms its input into output
    and must store any necessary parameters.
    Note that some modules do not require any parameters at all.
    Finally a module must possess a backpropagation method,
    for purposes of calculating gradients.
    Fortunately, due to some behind-the-scenes magic
    supplied by the auto differentiation
    (introduced in :numref:`sec_autograd`)
    when defining our own module,
    we only need to worry about parameters
    and the forward propagation method.
    """


    6.1 Layers and modules , go through: yes, exercise: 

    6.2 Parameter management, go through: yes, exercise: 

    6.3 Parameter initialization, go through: yes, exercise: 

    6.4 Lazzy Initialization, go through: yes, exercise: 

    6.5 Custom layers, go through: yes, exercise: 

    6.6 File I/O, go through:  yes, exercise:
    """
    However, at some point we will hopefully be happy enough with the learned models that we will want to save the results for later use in various contexts (perhaps even to make predictions in deployment). 
    
    Additionally, when running a long training process, the best practice is to periodically save intermediate results (checkpointing) to ensure that we do not lose several days’ worth of computation if we trip over the power cord of our server. 
    """ 

    6.7 GPUs, go through: , exercise: 

    , go through: , exercise: 

    

    ...


    9. Recurrent neural networks
        9.1 working with sequences,  go through: , exercise: 
        , go through: , exercise: 
        , go through: , exercise: 
        , go through: , exercise: 
