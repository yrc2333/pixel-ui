<template>
  <div class="tooltip-base-box">
    <div class="row center">
      <px-tooltip
        class="box-item"
        content="Top Left prompts info"
        placement="top-start"
      >
        <px-button>top-start</px-button>
      </px-tooltip>
      <px-tooltip
        class="box-item"
        content="Top Center prompts info"
        placement="top"
      >
        <px-button>top</px-button>
      </px-tooltip>
      <px-tooltip
        class="box-item"
        content="Top Right prompts info"
        placement="top-end"
      >
        <px-button>top-end</px-button>
      </px-tooltip>
    </div>
    <div class="row">
      <px-tooltip
        class="box-item"
        content="Left Top prompts info"
        placement="left-start"
      >
        <px-button>left-start</px-button>
      </px-tooltip>
      <px-tooltip
        class="box-item"
        content="Right Top prompts info"
        placement="right-start"
      >
        <px-button>right-start</px-button>
      </px-tooltip>
    </div>
    <div class="row">
      <px-tooltip
        class="box-item"
        content="Left Center prompts info"
        placement="left"
      >
        <px-button class="mt-3 mb-3">left</px-button>
      </px-tooltip>
      <px-tooltip
        class="box-item"
        content="Right Center prompts info"
        placement="right"
      >
        <px-button>right</px-button>
      </px-tooltip>
    </div>
    <div class="row">
      <px-tooltip
        class="box-item"
        content="Left Bottom prompts info"
        placement="left-end"
      >
        <px-button>left-end</px-button>
      </px-tooltip>
      <px-tooltip
        class="box-item"
        content="Right Bottom prompts info"
        placement="right-end"
      >
        <px-button>right-end</px-button>
      </px-tooltip>
    </div>
    <div class="row center">
      <px-tooltip
        class="box-item"
        content="Bottom Left prompts info"
        placement="bottom-start"
      >
        <px-button>bottom-start</px-button>
      </px-tooltip>
      <px-tooltip
        class="box-item"
        content="Bottom Center prompts info"
        placement="bottom"
      >
        <px-button>bottom</px-button>
      </px-tooltip>
      <px-tooltip
        class="box-item"
        content="Bottom Right prompts info"
        placement="bottom-end"
      >
        <px-button>bottom-end</px-button>
      </px-tooltip>
    </div>
  </div>
</template>

<style>
.tooltip-base-box .row {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.tooltip-base-box .center {
  justify-content: center;
}
.tooltip-base-box .box-item {
  margin-top: 10px;
}
</style>
