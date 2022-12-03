# Module_5

In this challenge I am working at a fintech consulting firm that aims to benefit local communities. Our first contract is with a large credit union. During this challenge I built a tool that helps credit union members evaluate their financial health. The credit union wants their members to be able to do two things; assess their monthly budgets, and forecast a reasonably effective retirement plan based on their current holdings. I created a financial planner for emergencies and a financial planner for retirement.

Installation Guide

Before running the application first install the following dependencies.
 
import os
import requests
import json
import pandas as pd
from dotenv import load_dotenv
import alpaca_trade_api as tradeapi
from MCForecastTools import MCSimulation

%matplotlib inline
