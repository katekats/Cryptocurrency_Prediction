# Cryptocurrency_Prediction

We predict cryptocurrency prices based on past prices and sentiment scores from tweets. The sentiment score is calculated with the Vader lexicon. We perform Fractional differencing to avoid the information loss that happens when we use differencing to make the price time series stationary. The intuition for using fractional differencing is described in the Book [Advances in Financial Machine Learning](https://lesen.amazon.de/kp/embed?preview=newtab&linkCode=kpe&ref_=cm_sw_r_kb_dp_wLk0FbAJE9SSA&asin=B079KLDW21&reshareId=06D1DT59VSRSZ9KHGRDW&reshareChannel=system)
