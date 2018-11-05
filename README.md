# ARCH-model
Modelling returns, or financial data, is always challenging due to the leptokurtic feature of this type of data. Because of that, normal model with homoskedasticity is not suitable in this task.
Over the time, many models have been born to fit returns, and in this section, we will try to apply the simplest model, which is ARCH(1).
In detail, the time series is modelled by AR(2) process with the error terms following ARCH(1) model. Detail of the model would be introduced in the code.
I use Maximum Likelihood method to estimate this model and some numerical optimization methods.
