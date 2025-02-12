---
description: Hooking into validation events within Umbraco Commerce.
---

# List of Validation Events

{% hint style="warning" %}
This article is a work in progress and may undergo further revisions, updates, or amendments. The information contained herein is subject to change without notice.
{% endhint %}

## <code>Umbraco.Commerce.Core.Events.Validation</code>

<table>
  <thead>
    <tr>
      <th>Event</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ValidateCancelOrderPayment</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateCaptureOrderPayment</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateCountryCodeChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateCountryCreate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateCountryDefaultCurrencyChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateCountryDefaultPaymentMethodChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateCountryDefaultShippingMethodChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateCountryDelete</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateCountryNameChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateCountrySave</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateCountryUpdate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateCurrencyAllowInCountry</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateCurrencyCodeChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateCurrencyCreate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateCurrencyCultureChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateCurrencyCustomFormatTemplateChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateCurrencyDelete</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateCurrencyDisallowInCountry</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateCurrencyNameChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateCurrencySave</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateCurrencyUpdate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateDiscountActiveChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateDiscountAliasChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateDiscountCodeAdd</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateDiscountCodeChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateDiscountCodeRemove</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateDiscountCreate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateDiscountDateRangeChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateDiscountDelete</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateDiscountNameChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateDiscountRewardsChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateDiscountRulesChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateDiscountSave</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateDiscountTypeChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateDiscountUpdate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateEmailTemplateAliasChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateEmailTemplateBccAddressChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateEmailTemplateCategoryChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateEmailTemplateCcAddressChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateEmailTemplateCreate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateEmailTemplateDelete</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateEmailTemplateNameChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateEmailTemplateReplyToAddressChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateEmailTemplateSave</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateEmailTemplateSenderChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateEmailTemplateSendToCustomerChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateEmailTemplateSubjectChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateEmailTemplateToAddressChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateEmailTemplateUpdate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateEmailTemplateViewChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateExportTemplateAliasChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateExportTemplateCategoryChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateExportTemplateCreate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateExportTemplateDelete</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateExportTemplateExportStrategyChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateExportTemplateFileExtensionChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateExportTemplateFileMimeTypeChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateExportTemplateNameChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateExportTemplateSave</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateExportTemplateUpdate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateExportTemplateViewChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateFetchOrderPaymentStatus</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateGiftCardActiveChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateGiftCardAmountsChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateGiftCardCodeChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateGiftCardCreate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateGiftCardCurrencyChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateGiftCardDelete</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateGiftCardExpiryDateChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateGiftCardOrderChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateGiftCardPropertyChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateGiftCardSave</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateGiftCardUpdate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateLocationAddressChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateLocationAliasChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateLocationCreate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateLocationDelete</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateLocationNameChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateLocationSave</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateLocationTypeChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateLocationUpdate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderAssignToCustomer</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderCodeEvent</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderCreate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderCurrencyChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderDelete</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderDiscountCodeRedeem</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderDiscountCodeUnredeem</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderFinalize</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderGiftCardRedeem</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderGiftCardUnredeem</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderLanguageChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderLinePropertyChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderLineQuantityChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderLineRemove</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderLineTaxClassChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderPaymentCountryRegionChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderPaymentMethodChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderProductAdd</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderPropertyChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderSave</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderShippingCountryRegionChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderShippingMethodChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderStatusAliasChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderStatusChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderStatusColorChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderStatusCreate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderStatusDelete</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderStatusNameChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderStatusSave</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderStatusUpdate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderTagAdd</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderTagRemove</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderTaxClassChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderTransactionUpdate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderUpdate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidatePaymentMethodAliasChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidatePaymentMethodAllowInCountryRegion</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidatePaymentMethodClearPrices</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidatePaymentMethodCreate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidatePaymentMethodDelete</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidatePaymentMethodDisallowInCountryRegion</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidatePaymentMethodImageChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidatePaymentMethodNameChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidatePaymentMethodPriceChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidatePaymentMethodSave</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidatePaymentMethodSettingChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidatePaymentMethodSkuChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidatePaymentMethodTaxClassChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidatePaymentMethodToggleFeatures</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidatePaymentMethodUpdate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidatePrintTemplateAliasChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidatePrintTemplateCategoryChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidatePrintTemplateCreate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidatePrintTemplateDelete</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidatePrintTemplateNameChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidatePrintTemplateSave</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidatePrintTemplateUpdate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidatePrintTemplateViewChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateProductAttributeAliasChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateProductAttributeCreate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateProductAttributeDelete</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateProductAttributeNameChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateProductAttributePresetAliasChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateProductAttributePresetAllowAttribute</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateProductAttributePresetCreate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateProductAttributePresetDelete</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateProductAttributePresetDescriptionChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateProductAttributePresetDisallowAttribute</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateProductAttributePresetIconChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateProductAttributePresetNameChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateProductAttributePresetSave</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateProductAttributePresetUpdate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateProductAttributeSave</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateProductAttributeUpdate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateProductAttributeValueAdd</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateProductAttributeValueNameChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateProductAttributeValueRemove</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateRefundOrderPayment</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateRegionCodeChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateRegionCreate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateRegionDefaultPaymentMethodChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateRegionDefaultShippingMethodChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateRegionDelete</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateRegionNameChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateRegionSave</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateRegionUpdate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateShippingMethodAliasChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateShippingMethodAllowInCountryRegion</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateShippingMethodCalculationConfigChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateShippingMethodClearPrices</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateShippingMethodCreate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateShippingMethodDelete</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateShippingMethodDisallowInCountryRegion</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateShippingMethodImageChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateShippingMethodNameChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateShippingMethodPriceChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateShippingMethodSave</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateShippingMethodSettingChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateShippingMethodSkuChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateShippingMethodTaxClassChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateShippingMethodUpdate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStockChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStoreAddGiftCardPropertyAlias</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStoreAddProductPropertyAlias</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStoreAddProductUniquenessPropertyAlias</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStoreAliasChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStoreAllowUser</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStoreAllowUserRole</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStoreBaseCurrencyChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStoreCookiesChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStoreCreate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStoreDefaultCountryChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStoreDefaultLocationChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStoreDefaultTaxClassChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStoreDelete</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStoreDisallowUser</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStoreDisallowUserRole</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStoreGiftCardSettingsChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStoreMeasurementSystemChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStoreNameChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStoreNotificationEmailTemplatesChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStoreOrderNumberTemplatesChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStoreOrderRoundingMethodChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStoreOrderStatusesChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStorePriceTaxInclusivityChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStoreRemoveGiftCardPropertyAlias</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStoreRemoveProductPropertyAlias</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStoreRemoveProductUniquenessPropertyAlias</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStoreSave</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStoreShareStockFromStoreChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateStoreUpdate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateTaxClassAliasChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateTaxClassClearTaxRates</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateTaxClassCreate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateTaxClassDelete</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateTaxClassNameChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateTaxClassSave</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateTaxClassTaxRateChange</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateTaxClassUpdate</td>
      <td></td>
    </tr>
  </tbody>
</table>

## <code>Umbraco.Commerce.Core.Events.Validation.Handlers.Country</code>

<table>
  <thead>
    <tr>
      <th>Event</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ValidateCountryCodeFormat</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateDefaultCurrencyBelongsToCountryStore</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateDefaultPaymentMethodBelongsToCountryStore</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateDefaultShippingMethodBelongsToCountryStore</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateNotStoreDefaultCountry</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateUniqueCountryCode</td>
      <td></td>
    </tr>
  </tbody>
</table>

## <code>Umbraco.Commerce.Core.Events.Validation.Handlers.Currency</code>

<table>
  <thead>
    <tr>
      <th>Event</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ValidateAllowedCountryBelongsToCurrencyStore</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateCulture</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateCurrencyCodeFormat</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateNotCountryDefaultCurrency</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateNotStoreBaseCurrency</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateUniqueCurrencyCode</td>
      <td></td>
    </tr>
  </tbody>
</table>

## <code>Umbraco.Commerce.Core.Events.Validation.Handlers.Discount</code>

<table>
  <thead>
    <tr>
      <th>Event</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ValidateUniqueAlias</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateUniqueDiscountCode</td>
      <td></td>
    </tr>
  </tbody>
</table>

## <code>Umbraco.Commerce.Core.Events.Validation.Handlers.EmailTemplate</code>

<table>
  <thead>
    <tr>
      <th>Event</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ValidateNotStoreDefaultEmailTemplate</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateUniqueEmailTemplateAlias</td>
      <td></td>
    </tr>
  </tbody>
</table>

## <code>Umbraco.Commerce.Core.Events.Validation.Handlers.ExportTemplate</code>

<table>
  <thead>
    <tr>
      <th>Event</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ValidateUniqueExportTemplateAlias</td>
      <td></td>
    </tr>
  </tbody>
</table>

## <code>Umbraco.Commerce.Core.Events.Validation.Handlers.GiftCard</code>

<table>
  <thead>
    <tr>
      <th>Event</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ValidateUniqueGiftCardCode</td>
      <td></td>
    </tr>
  </tbody>
</table>

## <code>Umbraco.Commerce.Core.Events.Validation.Handlers.Location</code>

<table>
  <thead>
    <tr>
      <th>Event</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ValidateNotStoreDefaultLocation</td>
      <td></td>
    </tr>
  </tbody>
</table>

## <code>Umbraco.Commerce.Core.Events.Validation.Handlers.Order</code>

<table>
  <thead>
    <tr>
      <th>Event</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ValidateCurrencyBelongsToOrderStore</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateDiscountCodeValid</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateGiftCardPropertyIsWritable</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateGiftCardValid</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderPaymentCountryRegionAllowedByOrderCurrency</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderPaymentCountryRegionBelongsToOrderStore</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderPropertyIsWritable</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderShippingCountryRegionBelongsToOrderStore</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderStatusBelongsToOrderStore</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderStatusCode</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidatePaymentMethodAllowedInPaymentCountryRegion</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidatePaymentMethodBelongsToOrderStore</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateProductAddHasPrice</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateProductAddQuantityPositive</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateShippingMethodAllowedInShippingCountryRegion</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateShippingMethodBelongsToOrderStore</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateTaxClassBelongsToOrderStore</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateTransactionInitialized</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateUniqueBundleId</td>
      <td></td>
    </tr>
  </tbody>
</table>

## <code>Umbraco.Commerce.Core.Events.Validation.Handlers.OrderLine</code>

<table>
  <thead>
    <tr>
      <th>Event</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ValidateOrderLinePropertyIsWritable</td>
      <td></td>
    </tr>
  </tbody>
</table>

## <code>Umbraco.Commerce.Core.Events.Validation.Handlers.OrderStatus</code>

<table>
  <thead>
    <tr>
      <th>Event</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ValidateNotStoreDefaultOrderStatus</td>
      <td></td>
    </tr>
  </tbody>
</table>

## <code>Umbraco.Commerce.Core.Events.Validation.Handlers.PaymentMethod</code>

<table>
  <thead>
    <tr>
      <th>Event</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ValidateAllowedInPriceCountryRegion</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateNotCountryDefaultPaymentMethod</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateNotRegionDefaultPaymentMethod</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateUniquePaymentMethodAlias</td>
      <td></td>
    </tr>
  </tbody>
</table>

## <code>Umbraco.Commerce.Core.Events.Validation.Handlers.PrintTemplate</code>

<table>
  <thead>
    <tr>
      <th>Event</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ValidateUniquePrintTemplateAlias</td>
      <td></td>
    </tr>
  </tbody>
</table>

## <code>Umbraco.Commerce.Core.Events.Validation.Handlers.ProductAttribute</code>

<table>
  <thead>
    <tr>
      <th>Event</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ValidateUniqueProductAttributeAlias</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateUniqueProductAttributePresetAlias</td>
      <td></td>
    </tr>
  </tbody>
</table>

## <code>Umbraco.Commerce.Core.Events.Validation.Handlers.Region</code>

<table>
  <thead>
    <tr>
      <th>Event</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ValidateDefaultPaymentMethodBelongsToRegionStore</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateDefaultShippingMethodBelongsToRegionStore</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateUniqueRegionCode</td>
      <td></td>
    </tr>
  </tbody>
</table>

## <code>Umbraco.Commerce.Core.Events.Validation.Handlers.ShippingMethod</code>

<table>
  <thead>
    <tr>
      <th>Event</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ValidateAllowedInPriceCountryRegion</td>
      <td>OBSOLETE: Use <code>ValidateFixedRateAllowedInPriceCountryRegion</code> instead.</td>
    </tr>
    <tr>
      <td>ValidateCalculationModeConfigType</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateFixedRateAllowedInPriceCountryRegion</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateNotCountryDefaultShippingMethod</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateNotRegionDefaultShippingMethod</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateUniqueShippingMethodAlias</td>
      <td></td>
    </tr>
  </tbody>
</table>

## <code>Umbraco.Commerce.Core.Events.Validation.Handlers.Store</code>

<table>
  <thead>
    <tr>
      <th>Event</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ValidateDefaultCountryBelongsToStore</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateDefaultTaxClassBelongsToStore</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateNotificationEmailTemplatesBelongsToStore</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateOrderStatusesBelongsToStore</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateUniqueStoreAlias</td>
      <td></td>
    </tr>
  </tbody>
</table>

## <code>Umbraco.Commerce.Core.Events.Validation.Handlers.TaxClass</code>

<table>
  <thead>
    <tr>
      <th>Event</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ValidateNotStoreDefaultTaxClass</td>
      <td></td>
    </tr>
    <tr>
      <td>ValidateUniqueTaxClassAlias</td>
      <td></td>
    </tr>
  </tbody>
</table>
