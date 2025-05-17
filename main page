# This page needs to be built out
import dash
from dash import html, dcc, Input, Output
import dash_mantine_components as dmc
from dash_auth import public_callback

dash.register_page(__name__,path='/')

layout = html.Div([
        dmc.Header(
            height=60, children=[dmc.Text("VOST response reporting")], style={"backgroundColor": "#9c86e2"}
        ),
        dmc.Container(
            id="home-contents",
            children=[dmc.Text("test for interactivity")]
        ),
        dmc.Button(
            "Report",
            id="home-button",
            color="orange",
            fullWidth=True,
        )

])
